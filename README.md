<!--
   Copyright 2022 Stamatis Zampetakis

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
-->
# DBMS resources

A curated list of interesting research papers and technical reports around data management on areas of personal interest.
An extended and more complete list of resources is maintained [here](https://github.com/pingcap/awesome-database-learning).

## Query processing

- 1979, [Access Path Selection in a Relational Database Management System](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.71.3735&rep=rep1&type=pdf), SIGMOD
- 1981, [Query Processing in a System for Distributed Databases (SDD-1)](https://dl.acm.org/doi/pdf/10.1145/319628.319650?casa_token=ur4Gu100MIYAAAAA:vhgA_e5VfGWostErZEbns9STblaiLq2lgMbRN7ZdujWLlCWAOrDVdUbfRfq-aO9jpHcMCx0MMm9KkA), TODS
- 1993, [The Volcano Optimizer Generator- Extensibility and Efficient Search](https://pdfs.semanticscholar.org/a817/a3e74d1663d9eb35b4baf3161ab16f57df85.pdf), ICDE
- 1995, [The Cascades Framework for Query Optimization](https://pdfs.semanticscholar.org/360e/cdfc79850873162ee4185bed8f334da30031.pdf), IEEE Data engineering Bulltin
- 2001, [Block oriented processing of Relational Database operations in modern Computer Architectures](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.137.6207&rep=rep1&type=pdf), ICDE
- 2015, [How Good Are Query Optimizers, Really?](https://www.vldb.org/pvldb/vol9/p204-leis.pdf), VLDB
- 2018, [Query Optimization Through the Looking Glass, and What We Found Running the Join Order Benchmark](https://db.in.tum.de/~leis/papers/lookingglass.pdf), PVLDB

## Join enumeration

- 2008, [Dynamic Programming Strikes Back](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.323.5901&rep=rep1&type=pdf), SIGMOD
- 2013, [On the Correct and Complete Enumeration of the Core Search Space](https://dl.acm.org/doi/pdf/10.1145/2463676.2465314?casa_token=yvcnfhQv5CoAAAAA:MXIsF0r8bIh1rYUJGTHf4nX67Mo1Ma_SCSwT1S8P6EERY1e-TaHlf7Aj7KDBarZTmXsocxXKOoj4tQ), SIGMOD
- 2014, [Optimizing Join Enumeration in Transformation-based Query Optimizers](https://dl.acm.org/doi/pdf/10.14778/2732977.2732997?casa_token=kEIsqb2PIwcAAAAA:6zoDCX1UV86EfqTw6NhypZhMNWgrzxv55jdAkCs4iVlH03nJ4LTjbpLpkOfrkPcW8sBhn7C4WOYbuA), VLDB
- 2018, [Adaptive Optimization of Very Large Join Queries](https://db.in.tum.de/~radke/papers/hugejoins.pdf), SIGMOD

## Join algorithms

- 1989, [A Performance Evaluation of Four Parallel Join Algorithms in a Shared-Nothing Multiprocessor Environment](https://dl.acm.org/doi/pdf/10.1145/66926.66937?casa_token=Un-_2D0Tj50AAAAA:887uLDeyhMXAc8GJ8UhQ4lrKwLKmehcfIDIeKRhvj5ZKjxs34SsqFMXxRfWifesLvef70G0Mbf1oqQ), SIGMOD

## Semijoin reducers

- 2001, [Integrating Semi-Join-Reducers into State-of-the-Art Query Processors](https://db.in.tum.de/research/publications/conferences/semijoin.pdf), ICDE

## Subqueries

- 1996, [Complex query decorrelation](https://ieeexplore.ieee.org/abstract/document/492194), ICDE
- 2015, (https://btw-2015.informatik.uni-hamburg.de/res/proceedings/Hauptband/Wiss/Neumann-Unnesting_Arbitrary_Querie.pdf), BTW

## Bloom filters

- 2019, [Performance-Optimal Filtering: Bloom Overtakes Cuckoo at High Throughput](https://dl.acm.org/doi/pdf/10.14778/3303753.3303757?casa_token=s7bonkkd2wYAAAAA:5_9gaE-fiUcLJ-BID4B9nW_TRxbcjFbjr8d_Dn7EuVCzmkdU839Kjkrv6_yFR3YtCDo224_TJFIIUQ), VLDB

## Sampling & Approximate query answering

- 2018, [Random Sampling over Joins Revisited](https://www.cs.utah.edu/~lifeifei/papers/samplejoin.pdf), SIGMOD

## Statistics

- 2017, [Cardinality Estimation Done Right: Index-Based Join Sampling](http://cidrdb.org/cidr2017/papers/p9-leis-cidr17.pdf), CIDR

## Column stores

- 2008, [Column-Stores vs. Row-Stores: How Different Are They Really?](https://www.inf.ufpr.br/eduardo/ensino/ci809/papers/p967-abadi.pdf), SIGMOD

## View recommendations

- 2020, [Automated Generation of Materialized Views in Oracle](https://dl.acm.org/doi/pdf/10.14778/3415478.3415533?casa_token=gE_xX6dy0AwAAAAA:u-nBW4z0N2lZ8a-auiaNhfIK2vHsMORWkAVON69eqyJEIudzqxChNU_4ACZjgbaikmiyTfdKqPA1aQ), VLDB

## Data management systems

- 2010, [The Hadoop Distributed File System](http://docentes.uaa.mx/luisbautista/download/The%20HDFS.pdf), MSST
- 2014, [Distributed Data Management Using MapReduce](https://dl.acm.org/doi/pdf/10.1145/2503009?casa_token=sZIDzbfiwrsAAAAA:HREYEPFdw2OQ5aY6eoRics_wgmZgkjsqe8SDVjHI1XwReJYulMV32GpPDu_ODuJgb83Z-he9HnOM5g), CSUR
- 2015, [Apache Tez: A Unifying Framework for Modeling and Building Data Processing Applications](http://home.cse.ust.hk/~weiwa/teaching/Fall15-COMP6611B/reading_list/Tez.pdf), SIGMOD
