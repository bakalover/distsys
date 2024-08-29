## Distributed systems
Collection of papers/lectures/talks etc generally about distributed systems and adjacent themes.
***
Tags:
***
### 🌐 General
+ [Consistency models](https://jepsen.io/consistency)
+ [Graph Theory](https://logic.pdmi.ras.ru/~dvk/graphs_dk.pdf)
+ [Time, Clocks, and the Ordering of Events in a Distributed System](https://lamport.azurewebsites.net/pubs/time-clocks.pdf)
+ [A Science of Concurrent Programs](https://lamport.azurewebsites.net/tla/science.pdf)
+ [The Art of Multiprocessor Programming by Maurice Herlihy & Nir Shavit](https://github.com/amilajack/reading/blob/master/Computer_Science/The%20Art%20of%20Multiprocessor%20Programming.pdf)
***
### 🤝 Consensus
+ Paxos (see paxosmon list below):
  + [The Part-Time Parliament](https://lamport.azurewebsites.net/pubs/lamport-paxos.pdf)
  + [Paxos Made Simple](https://lamport.azurewebsites.net/pubs/paxos-simple.pdf)
  + [Paxos Made Live](https://www.cs.utexas.edu/users/lorenzo/corsi/cs380d/papers/paper2-1.pdf)
+ Raft:
  + [In Search of an Understandable Consensus Algorithm(Extended Version)](https://raft.github.io/raft.pdf)
  + [Повышаем живучесть Raft в реальных условиях / Сергей Останевич (Tarantool, VK)](https://youtu.be/GxvFdTqs3-I?si=blSsA5Lb-uXF1EYK)
+ [Heidi Howard — Paxos vs Raft: Have we reached consensus on distributed consensus?](https://youtu.be/0K6kt39wyH0?si=KyWtwr-w3g7vqG69)
+ [Viewstamped Replication: A New Primary Copy Method to Support Highly-Available Distributed Systems](https://pmg.csail.mit.edu/papers/vr.pdf)
+ 💸 BFT & Crypto:
  + [The Byzantine Generals](https://lamport.azurewebsites.net/pubs/the-byz-generals.pdf)
  + [Bitcoin](https://bitcoin.org/bitcoin.pdf)
  + TON:
    + [The Open Network (White paper)](https://docs.ton.org/ton.pdf)
    + [Telegram Open Network Blockchain](https://docs.ton.org/tblkch.pdf)
    + [Catchain Consensus: An Outline](https://docs.ton.org/catchain.pdf)
  + Ethereum:
    + [Ethereum: A Next-Generation Smart Contract and Decentralized Application Platform (White paper)](https://ethereum.org/content/whitepaper/whitepaper-pdf/Ethereum_Whitepaper_-_Buterin_2014.pdf)
    + [ETHEREUM: A SECURE DECENTRALISED GENERALISED TRANSACTION LEDGER (Yellow paper)](https://ethereum.github.io/yellowpaper/paper.pdf)
  + [Asynchronous Consensus without Trusted Setup or Public-KeyCryptography](https://eprint.iacr.org/2024/677.pdf)
  + [Practical Byzantine Fault Tolerance](https://pmg.csail.mit.edu/papers/osdi99.pdf)
  + [HotStuff: BFT Consensus in the Lens of Blockchain](https://arxiv.org/pdf/1803.05069)
  + [Tendermint: Consensus without Mining](https://tendermint.com/static/docs/tendermint.pdf)
***
### 🤫 Gossip/Infectioning
+ [SWIM: Scalable Weakly-consistent Infection-style Process Group Membership Protocol](https://www.cs.cornell.edu/projects/Quicksilver/public_pdfs/SWIM.pdf)
***
### 💯 Transactions
+ [Distributed Transaction Processing: The XA Specification](https://pubs.opengroup.org/onlinepubs/009680699/toc.pdf)
+ [Two Phase Locking (2PL)](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/05/chapter3.pdf)
+ Detetministic:
  + [Распределенные транзакции в YDB / Семён Чечеринда (Яндекс)](https://youtu.be/8AR1u5OZIm8?si=PFz6sznlm2lLj_xc)
  + [Calvin: Fast Distributed Transactions for Partitioned Database Systems](https://cs.yale.edu/homes/thomson/publications/calvin-sigmod12.pdf)
+ [Maurice Herlihy — Transactional memory](https://youtu.be/EGlcl1rGj1E?si=gqhJJekdXqux0rwy)
+ [The hitchhiker's guide to distributed transactions](https://youtu.be/sD5L5Utlq5g?si=GHlKolJ-ve8LH5rk)
+ [Hermitage](https://github.com/ept/hermitage)
***
### 👥 CRDT
+ [CRDTs: The hard parts](https://youtu.be/PMVBuMK_pJY?si=SJGG6rrkz_rRFLVV)
+ [Automerge](https://github.com/automerge/automerge-classic)
***
### 🔬 Testing & Verification
+ [Testing Distributed Systems](https://asatarin.github.io/testing-distributed-systems/)
+ [TLA+](https://lamport.azurewebsites.net/tla/tla.html)
+ [Designing distributed systems with TLA+](https://youtu.be/2PIgZ6hd-6I?si=xXzjjl1-VrJvfU06)
+ [Testing Distributed Systems w/ Deterministic Simulation" by Will Wilson](https://youtu.be/4fFDFbi3toc?si=VT3fsqLI2XSOPfu6)
+ [Jepsen](https://jepsen.io/)
***
### 🖌️ System Design
+ [Seven Sketches in Compositionality](https://arxiv.org/pdf/1803.05316)
+ [Clean Architecture](https://github.com/GunterMueller/Books-3/blob/master/Clean%20Architecture%20A%20Craftsman%20Guide%20to%20Software%20Structure%20and%20Design.pdf)
+ [Data Intensive Applications](https://github.com/lafengnan/ebooks-1/blob/master/Designing%20Data%20Intensive%20Applications.pdf)
***
### 🎛️ Management & Scheduling
+ [Large-scale cluster management at Google with Borg](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/43438.pdf)
+ [Quincy: Fair Scheduling for Distributed Computing Clusters](https://www.sigops.org/s/conferences/sosp/2009/papers/isard-sosp09.pdf)
***
### ⚙️ Misc
+ [Dynamo: Amazon’s Highly Available Key-value Store](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)
+ [Cassandra - A Decentralized Structured Storage System](https://www.cs.cornell.edu/projects/ladis2009/papers/lakshman-ladis2009.pdf)
+ Kafka:
    + [Confluent blog](https://www.confluent.io/blog/)
    + [Kafka: a Distributed Messaging System for Log Processing](https://notes.stephenholiday.com/Kafka.pdf)
    + [Book](https://book.huihoo.com/pdf/confluent-kafka-definitive-guide-complete.pdf)
+ [ZooKeeper: A Distributed Coordination Service for Distributed](https://zookeeper.apache.org/doc/r3.2.2/zookeeperOver.pdf)
+ [Large-scale Incremental Processing Using Distributed Transactions and Notifications (Percolator)](https://storage.googleapis.com/gweb-research2023-media/pubtools/pdf/36726.pdf)
+ [Spanner: Google’s Globally-Distributed Database](https://research.google.com/archive/spanner-osdi2012.pdf)
+ [Bigtable: A Distributed Storage System for Structured Data](https://storage.googleapis.com/gweb-research2023-media/pubtools/pdf/68a74a85e1662fe02ff3967497f31fda7f32225c.pdf)
+ [The Chubby lock service for loosely-coupled distributed systems](https://research.google.com/archive/chubby-osdi06.pdf)
+ [Kademlia: A Peer-to-peer Information System Based on the XOR Metric](https://pdos.csail.mit.edu/~petar/papers/maymounkov-kademlia-lncs.pdf)
+ [Просто о сложном как работает драйвер распределенной базы данных YDB / Алексей Мясников](https://youtu.be/bbdk2UGkWR8?si=63REowfjWR9gqqaP)
+ [ETCD Key-Value](https://etcd.io/)
+ [YTsaurus](https://ytsaurus.tech/docs/en/)
+ [FoundationDB](https://www.foundationdb.org/files/fdb-paper.pdf)
***
### 📜 Related Lists
+ [Roman Lipovsky](https://gitlab.com/Lipovsky/awesome-distsys)
+ [Heidi Howard](https://github.com/heidihoward/distributed-consensus-reading-list)
+ [Paxosmon](https://vadosware.io/post/paxosmon-gotta-concensus-them-all/)
***
### 🔱 Advanced Concurrency
+ [Scalable Channel](https://arxiv.org/pdf/2211.04986)
+ [Nikita Koval — Synchronization primitives can be faster with SegmentQueueSynchronizer](https://youtu.be/2uxsNJ0TdIM?si=6V3TPxjHoXJlRXW6)
+ State Reduction Techniques:
    + [Truly Stateless, Optimal Dynamic Partial Order Reduction](https://plv.mpi-sws.org/genmc/popl2022-trust.pdf)
    + [A Practical Approach for Model Checking C/C++11 Code](http://plrg.eecs.uci.edu/publications/toplas16.pdf)
### 🕜 Await Queue

***
### 🌟 Conferences
+ [Hydra](https://hydraconf.com/)
+ [Highload++](https://highload.ru/)
