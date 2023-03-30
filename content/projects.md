---
title: "Projects"
---

## ClevelDB

[ClevelDB]()

## Conclave

[Conclave](https://github.com/nitinsavant/cleveldb) is my attempt to build a clone of ]LevelDB](https://en.wikipedia.org/wiki/LevelDB) in order to explore many of its key ideas, including:

-A skip list (i.e. memtable) to support fast retrieval of the most recent db writes
- A write-ahead-log (i.e. journal) to add basic persistence and support recovery in the event of a crash
- SSTables to flush older data to disk that won't fit in memory
- On-disk indexes to improve performance when searching SSTables
- Bloom Filter to improve performance when searching SSTables


## My Lists

*]My Lists](https://github.com/nitinsavant/lists)* was the first web app I wrote, and I still use it to keep track of the [movies](https://nitinsavant.herokuapp.com/lists/movies) and [books](https://nitinsavant.herokuapp.com/lists/books) that I've enjoyed.
