# Raft_implementation
This project is a distributed key-value store based on the Raft consensus algorithm developed in GoLang. It is implemented to support concurrent requests utilizing Mutex, Channel, and Goroutine. It is tested under a simulated environment, which covers the circumstances such as network loss, network partition, and partial cluster down.  

Check here for a more thorough understanding -https://eli.thegreenplace.net/2020/implementing-raft-part-0-introduction/   

Credits to the Raft paper - https://raft.github.io/raft.pdf  

### MapReduce

### Raft
- [x] Leader election
- [x] Log
- [x] Persistence
- [x] Log compaction

### Fault-tolerant Key/Value Service
- [x] Key/value service without snapshots
- [x] Key/value service with snapshots

### Sharded Key/Value Service
