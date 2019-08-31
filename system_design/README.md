- [狗家system design小文档](https://docs.google.com/document/d/1Fd-97V5fMZjx5DxL2xjbqe5VL10WXxR2wuxqInCIFo4/edit#)
  - [GFS](https://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf)
    - 应用场景（大文件，序列读写多，修改少）
    - 架构（单主机，chunkserver多replicas，cache only metadata）
    - Single Server（如何减少压力和访问次数）
    - ChunkSize的权衡，hot spot问题
    - MetaData（内存数据结构，利用log持久化和备份，文件namespace层级式压缩）
    - Chunk Locations（not persistence，heartbeat动态更新）
    - Log系统（先Log再更新，batch log以削峰），Checkpoint（类B树结构，可直接映射到内存）
    - relaxed consistency model
    
    
