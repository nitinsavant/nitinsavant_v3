---
title: "Projects"
---

## ClevelDB (2023)

[ClevelDB](https://github.com/nitinsavant/cleveldb) is my attempt to build a clone of [LevelDB](https://en.wikipedia.org/wiki/LevelDB) in order to explore many of its key ideas, including:

- A skip list (i.e. memtable) to support fast retrieval of the most recent db writes
- A write-ahead-log (i.e. journal) to add basic persistence and support recovery in the event of a crash
- SSTables to flush older data to disk that no longer fits in memory (i.e. the memtable)
- On-disk indexes to improve performance when searching SSTables
- Bloom Filter to improve performance when searching SSTables

## Conclave (2018)

[Conclave](https://conclave-team.github.io/conclave-site/) is a real-time collaborative text editor built in JavaScript.

Intrigued by collaboration tools like Google Docs, we set out to build one from scratch. Conclave uses a *Conflict-Free Replicated Data Type (CRDT)* to make sure all users stay in-sync and *WebRTC* to allow users to communicate directly to one another without a central server. The result is a private and secure way for users to collaborate. 

Read our [case study](https://conclave-team.github.io/conclave-site/) to learn how we built it from scratch.

{{< youtube hy0ePbpna5Y >}}

## My Lists (2015)

*[My Lists](https://github.com/nitinsavant/lists)* was the first web app I wrote, and I still use it to keep track of the [movies](https://nitinsavant.herokuapp.com/lists/movies) and [books](https://nitinsavant.herokuapp.com/lists/books) that I've enjoyed.
