## Knowledge Archive
Collection of papers/lectures/talks etc generally about distributed systems and adjacent themes.
***
⚠️ **SUBJECTIVE OPINION** ⚠️ 

[Tiers](https://en.wikipedia.org/wiki/Tier_list): 🟥🟧🟨🟩🟦\
Tags:
***
### General
+ 🟥 [Consistency models](https://jepsen.io/consistency)
+ 🟥 [Graph Theory](https://logic.pdmi.ras.ru/~dvk/graphs_dk.pdf)
+ 🟥 [Time, Clocks, and the Ordering of Events in a Distributed System](https://lamport.azurewebsites.net/pubs/time-clocks.pdf)
+ [Clean Code](https://github.com/jnguyen095/clean-code/blob/master/Clean.Code.A.Handbook.of.Agile.Software.Craftsmanship.pdf)
+ [The Mythical Man Month](https://web.eecs.umich.edu/~weimerw/2018-481/readings/mythical-man-month.pdf)
***
### Consensus
+ Paxos (see paxosmon list below):
  + 🟥 [The Part-Time Parliament](https://lamport.azurewebsites.net/pubs/lamport-paxos.pdf)
  + [Paxos Made Simple](https://lamport.azurewebsites.net/pubs/paxos-simple.pdf)
  + [Paxos Made Live](https://www.cs.utexas.edu/users/lorenzo/corsi/cs380d/papers/paper2-1.pdf)
+ Raft:
  + 🟧 [Paper](https://raft.github.io/raft.pdf)
  + [Tuning](https://youtu.be/GxvFdTqs3-I?si=blSsA5Lb-uXF1EYK)
+ [Viewstamped Replication](https://pmg.csail.mit.edu/papers/vr.pdf)
- BFT & Crypto:
  - 🟥 [Byzantine Generals](https://lamport.azurewebsites.net/pubs/the-byz-generals.pdf)
  - 🟥 [Bitcoin](https://bitcoin.org/bitcoin.pdf)
  - TON:
    - [White paper](https://docs.ton.org/ton.pdf)
    - [Blockchain](https://docs.ton.org/tblkch.pdf)
    - 🟧 [Catchain Consensus](https://docs.ton.org/catchain.pdf)
  - Ethereum:
    - [White paper](https://ethereum.org/content/whitepaper/whitepaper-pdf/Ethereum_Whitepaper_-_Buterin_2014.pdf)
    - [Yellow paper](https://ethereum.github.io/yellowpaper/paper.pdf)
  - [Crypto-Free Consensus](https://eprint.iacr.org/2024/677.pdf)
  - 🟨 [PBFT](https://pmg.csail.mit.edu/papers/osdi99.pdf)
  - 🟧 [HotStuff BFT](https://arxiv.org/pdf/1803.05069)
***
### Transactions
+ 🟨 [XA spec](https://pubs.opengroup.org/onlinepubs/009680699/toc.pdf)
+ 🟩 [2PL](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/05/chapter3.pdf)
+ Detetministic:
  - [YDB Txn](https://youtu.be/8AR1u5OZIm8?si=PFz6sznlm2lLj_xc)
  - 🟥 [Calvin](https://cs.yale.edu/homes/thomson/publications/calvin-sigmod12.pdf)
+ 🟧 [Transactional Memory](https://youtu.be/EGlcl1rGj1E?si=gqhJJekdXqux0rwy)
+ [The hitchhiker's guide to distributed transactions](https://youtu.be/sD5L5Utlq5g?si=GHlKolJ-ve8LH5rk)
***
### CRDT
+ [CRDTs: The hard parts](https://youtu.be/PMVBuMK_pJY?si=SJGG6rrkz_rRFLVV)
***
### Testing & Verification
+ 🟥 [Testing](https://asatarin.github.io/testing-distributed-systems/)
+ [TLA+](https://lamport.azurewebsites.net/tla/tla.html)
+ [Designing distributed systems with TLA+](https://youtu.be/2PIgZ6hd-6I?si=xXzjjl1-VrJvfU06)
+ 🟥 [Determinism](https://youtu.be/4fFDFbi3toc?si=VT3fsqLI2XSOPfu6)
***
### System Design
+ 🟥 [Seven Sketches in Compositionality](https://arxiv.org/pdf/1803.05316)
+ 🟩 [Clean Architecture](https://github.com/GunterMueller/Books-3/blob/master/Clean%20Architecture%20A%20Craftsman%20Guide%20to%20Software%20Structure%20and%20Design.pdf)
+ 🟧 [Data Intensive Applications](https://github.com/lafengnan/ebooks-1/blob/master/Designing%20Data%20Intensive%20Applications.pdf)
***
### Systems
- [Dynamo](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)
- [Cassandra](https://www.cs.cornell.edu/projects/ladis2009/papers/lakshman-ladis2009.pdf)
- Kafka:
    - 🟨 [Confluent blog](https://www.confluent.io/blog/)
    - 🟥 [Paper](https://notes.stephenholiday.com/Kafka.pdf)
    - [Book](https://book.huihoo.com/pdf/confluent-kafka-definitive-guide-complete.pdf)
- 🟨 [ZooKeeper](https://zookeeper.apache.org/doc/r3.2.2/zookeeperOver.pdf)
- [Percolator](https://storage.googleapis.com/gweb-research2023-media/pubtools/pdf/36726.pdf)
- 🟧 [Spanner](https://research.google.com/archive/spanner-osdi2012.pdf)
- [BigTable](https://storage.googleapis.com/gweb-research2023-media/pubtools/pdf/68a74a85e1662fe02ff3967497f31fda7f32225c.pdf)
- [Chubby](https://research.google.com/archive/chubby-osdi06.pdf)
- [Kademlia HashTable](https://pdos.csail.mit.edu/~petar/papers/maymounkov-kademlia-lncs.pdf)
- 🟩 [YDB-SDK](https://youtu.be/bbdk2UGkWR8?si=63REowfjWR9gqqaP)
***
### Related Lists
+ 🟥 [Roman Lipovsky](https://gitlab.com/Lipovsky/awesome-distsys)
+ 🟥 [Heidi Howard](https://github.com/heidihoward/distributed-consensus-reading-list)
+ 🟧 [Paxosmon](https://vadosware.io/post/paxosmon-gotta-concensus-them-all/)
***
### Queue
+ [ETCD Key-Value](https://etcd.io/)
+ [Hashicorp Consul](https://www.datocms-assets.com/2885/1597077859-consul-life-of-a-packet-service-mesh-v11-digital.pdf)
+ [SWIM](https://www.cs.cornell.edu/projects/Quicksilver/public_pdfs/SWIM.pdf)
***
### Conferences
+ [Hydra](https://hydraconf.com/)
+ [Highload++](https://highload.ru/)
