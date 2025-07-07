# 目录结构
geecache/
  |--lru/
      |--lru.go // 缓存淘汰策略
  |--byteview.go // 缓存值的抽象和封装
  |--cache.go // 缓存的并发控制
  |--geecache.go // 与外部交互，控制缓存存储和获取的主流程
  |--http.go // 提供被其他节点访问的能力（基于http）
