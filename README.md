# joncwong's Reading List

These are research papers, white papers, documentation, or blog posts that I have found to be extremely useful in my self-studying ventures. These range from theorhetical concepts to practical day-to-day software/system knowledge. Please submit a PR if you have any suggestions :)

## Recommended Books/Series
- [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/)
- [System Design Primer](https://github.com/donnemartin/system-design-primer)
- [Designing Data-Intensive Applications](https://dataintensive.net/)
- [Database Internals](https://www.databass.dev/)
- [Distributed Systems](https://www.distributed-systems.net/index.php/books/ds3/)
- [Distributed Systems YouTube Course by Chris Colohan](https://www.youtube.com/watch?v=7VbL89mKK3M&list=PLOE1GTZ5ouRPbpTnrZ3Wqjamfwn_Q5Y9A)
  - [What could go wrong?](https://www.youtube.com/watch?v=C8nLSLs0fNw)

## Papers and Articles

### Operating Systems and Compute
- [Borg, Omega, and Kubernetes](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/44843.pdf)
- [Linux CGroups Documentation](https://www.kernel.org/doc/Documentation/cgroup-v1/cgroups.txt)
- [Docker Internals](http://docker-saigon.github.io/post/Docker-Internals/)
- [Green Threads](https://c9x.me/articles/gthreads/intro.html)
  - [Green Threads vs Native Threads (more in-depth)](https://wiki.c2.com/?GreenVsNativeThreads)
- [Linux Internals Blog](https://learnlinuxconcepts.blogspot.com/2014/10/this-blog-is-to-help-those-students-and.html)
- [eBPF](https://ebpf.io/)

### Distributed Systems Theory
- [Time, Clocks, and the Ordering of Events in a Distributed System (Lamport Clocks)](http://lamport.azurewebsites.net/pubs/time-clocks.pdf)
- [Virtual Time and Global States of Distributed Systems (Vector Clocks)](https://www.vs.inf.ethz.ch/publ/papers/VirtTimeGlobStates.pdf)
- [Brewer's Conjecture and the Feasibility of Consistent, Available, Partition-Tolerant Web Services (CAP)](https://users.ece.cmu.edu/~adrian/731-sp04/readings/GL-cap.pdf)
- [The Part-Time Parliament (original Paxos paper)](https://lamport.azurewebsites.net/pubs/lamport-paxos.pdf)
- [Paxos Made Simple](https://lamport.azurewebsites.net/pubs/paxos-simple.pdf)
- [In Search of an Understandable Consensus Algorithm (Raft)](https://pdos.csail.mit.edu/6.824/papers/raft-extended.pdf)

### Parallel/Distributed Systems and Databases
- [MapReduce: Simplified Data Processing on Large Clusters](https://pdos.csail.mit.edu/6.824/papers/mapreduce.pdf)
- [The Google File System](https://pdos.csail.mit.edu/6.824/papers/gfs.pdf)
- [ZooKeeper: Wait-free coordination for Internet-scale systems](https://www.usenix.org/legacy/events/atc10/tech/full_papers/Hunt.pdf)
- [The Design of a Practical System for Fault-tolerant Virtual Machines](https://pdos.csail.mit.edu/6.824/papers/vm-ft.pdf)
- [Dynamo: Amazon’s Highly Available Key-value Store](https://pdos.csail.mit.edu/6.824/papers/dynamo.pdf)
- [Resilient Distributed Datasets: A Fault-Tolerant Abstraction for
In-Memory Cluster Computing (Spark)](https://pdos.csail.mit.edu/6.824/papers/zaharia-spark.pdf)
- [Using Paxos to Build a Scalable, Consistent,
and Highly Available Datastore (Spinnaker)](https://pdos.csail.mit.edu/6.824/papers/spinnaker.pdf)
- [Bitcoin: A Peer-to-Peer Electronic Cash System](https://pdos.csail.mit.edu/6.824/papers/bitcoin.pdf)
- [Frangipani: A Scalable Distributed File System](https://pdos.csail.mit.edu/6.824/papers/thekkath-frangipani.pdf)
- [Scaling Distributed Machine Learning with the Parameter Server](https://pdos.csail.mit.edu/6.824/papers/parameter.pdf)
- [Kafka: a Distributed Messaging System for Log Processing](http://notes.stephenholiday.com/Kafka.pdf)
- [The Chubby lock service for loosely-coupled distributed systems](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/c64be13661eaea41dcc4fdd569be4858963b0bd3.pdf)
- [Bigtable: A Distributed Storage System for Structured Data](http://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf)
- [Dapper, a Large-Scale Distributed Systems Tracing Infrastructure](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/36356.pdf)
- [Amazon DynamoDB (Usenix ATC 2022)](https://www.usenix.org/system/files/atc22-elhemali.pdf)
- [What’s Really New with NewSQL?](https://db.cs.cmu.edu/papers/2016/pavlo-newsql-sigmodrec2016.pdf)
- [Spanner: Google's Globally Distributed Database](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/65b514eda12d025585183a641b5a9e096a3c4be5.pdf)
- [CockroachDB: The Resilient Geo-Distributed SQL Database](https://dl.acm.org/doi/pdf/10.1145/3318464.3386134)

### Machine Learning/Deep Learning
- [A fast learning algorithm for deep belief nets](https://www.cs.toronto.edu/~hinton/absps/fastnc.pdf)
- [Generative Adversarial Nets](https://papers.nips.cc/paper/5423-generative-adversarial-nets.pdf)
- [Attention Is All You Need](https://arxiv.org/pdf/1706.03762.pdf)
- [Machine Learning Operations (MLOps):
Overview, Definition, and Architecture](https://arxiv.org/pdf/2205.02302.pdf)

### Performance Engineering (mainly blog posts)
- [The C10K problem](http://www.kegel.com/c10k.html)
- [NGINX vs. Apache: Our View of a Decade-Old Question](https://www.nginx.com/blog/nginx-vs-apache-our-view/)
- [Basic NGINX](https://nginx.org/en/#basic_http_features)
- [SREcon: Performance Checklists for SREs 2016](http://www.brendangregg.com/blog/2016-05-04/srecon2016-perf-checklists-for-sres.html)
   - [Linux Performance Analysis in 60,000 Milliseconds](https://netflixtechblog.com/linux-performance-analysis-in-60-000-milliseconds-accc10403c55)
  
### Other Blog Posts
- [Notes on Distributed Systems for Young Bloods](https://www.somethingsimilar.com/2013/01/14/notes-on-distributed-systems-for-young-bloods/)
- [Please stop calling databases CP or AP](https://martin.kleppmann.com/2015/05/11/please-stop-calling-databases-cp-or-ap.html)
- [How to do distributed locking](https://martin.kleppmann.com/2016/02/08/how-to-do-distributed-locking.html)
- [Schema evolution in Avro, Protocol Buffers and Thrift](https://martin.kleppmann.com/2012/12/05/schema-evolution-in-avro-protocol-buffers-thrift.html)
- On Disk IO:
  - [Part 1: Flavors of IO](https://medium.com/databasss/on-disk-io-part-1-flavours-of-io-8e1ace1de017)
  - [Part 2: More Flavours of IO](https://medium.com/databasss/on-disk-io-part-2-more-flavours-of-io-c945db3edb13)
  - [Part 3: LSM Trees](https://medium.com/databasss/on-disk-io-part-3-lsm-trees-8b2da218496f)
  - [Part 4: B-Trees and RUM Conjecture](https://medium.com/databasss/on-disk-storage-part-4-b-trees-30791060741)
  - [Part 5: Access Patterns in LSM Trees](https://medium.com/databasss/on-disk-io-access-patterns-in-lsm-trees-2ba8dffc05f9)

### Industry Case Studies
- [Holistic Configuration Management at Facebook](https://research.fb.com/wp-content/uploads/2016/11/holistic-configuration-management-at-facebook.pdf)
- [Python at Netflix](https://netflixtechblog.com/python-at-netflix-bba45dae649e)
- [Netflix's Learnings From Adopting GraphQL](https://netflixtechblog.com/our-learnings-from-adopting-graphql-f099de39ae5f)
- [Scaling Time Series Data Storage Part I](https://netflixtechblog.com/scaling-time-series-data-storage-part-i-ec2b6d44ba39)
- [Scaling Time Series Data Storage Part II](https://netflixtechblog.com/scaling-time-series-data-storage-part-ii-d67939655586)
