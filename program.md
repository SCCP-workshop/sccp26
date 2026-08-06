---
title: Program
---

# Program

SCCP 2026 is a one-day workshop co-located with [VLDB 2026](https://vldb.org/2026/)
in Boston. Paper titles link to the camera-ready PDF where available.

Session times will be announced closer to the workshop.

---

## Friday, September 4, 2026


#### Keynote
_Speaker: Alexey Gotsman (IMDEA Software Institute and Amazon Web Services)_

**Testing Consistency of Distributed Databases at AWS**

Abstract: Checking whether a given database run is correct with respect to the intended isolation-level specification is often computationally hard. I will describe our ongoing work at Amazon Web Services on a tool that makes this problem tractable by exploiting database-internal information, such as transaction timestamps assigned by the concurrency control. I will also explain how we applied the tool to Aurora Limitless Database - a horizontally scalable variant of Aurora PostgreSQL with strongly consistent distributed transactions. Our tool uses concurrency-control information from a run of a distributed database, such as Aurora Limitless, to deterministically replay this run on a compatible non-distributed database, such as community PostgreSQL. Any mismatch in the database output signals a bug in the original run. This approach covers a large subset of SQL, including predicates and DDL statements, and faithfully checks the intricacies of isolation levels provided by PostgreSQL.

Bio: Alexey Gotsman is a Research Professor at the IMDEA Software Institute in Madrid, Spain and a Scholar at Amazon Web Services. He obtained his PhD at the University of Cambridge, UK. His research interests are in distributed computing, software verification and the combinations of the two.

#### Session 1: Checking Reality
_Session Chair: Si Liu (Texas A&amp;M University)_

[**Extending Elle for Transaction Workloads with Duplicate Values**](https://arxiv.org/pdf/2607.17515)  
_Zhiheng Cai (Tsinghua University), Si Liu (Texas A&amp;M University), Hengfeng Wei (Hunan University), Yuxing Chen (Renmin University of China)_

**[Efficient Black-Box Serializability Checking in the Presence of Range Predicates](papers/sccp26-serializability-range-predicates.pdf)**  
_Qikang Liu (Simon Fraser University), Si Liu (Texas A&amp;M University), Yuepeng Wang (Simon Fraser University)_

**[Specifying and Analyzing Transactional Consistency Models with Predicates](papers/sccp26-consistency-models-predicates.pdf)** (Extended Abstract)  
_Hengfeng Wei (Hunan University), Si Liu (Texas A&amp;M University), Yuxing Chen (Renmin University of China)_

#### Session 2: Who Broke Serializability and Snapshot Isolation?
_Session Chair: Shuai Mu (Stony Brook University)_

**[Diagnosing the Structure of Strict-Serializability Violations Across Spanner-like Read-Only Transaction Protocols](papers/sccp26-strict-serializability-violations.pdf)**  
_Sejong Kim (Korea University), Yon Dohn Chung (Korea University)_

**[Verified Key-Value Stores Satisfying Snapshot Isolation](papers/sccp26-verified-kv-snapshot-isolation.pdf)** (Extended Abstract)  
_Arnaud Daby-Seesaram (Aarhus University), Léon Ducruet (Aarhus University), Lars Birkedal (Aarhus University), Amin Timany (Aarhus University)_

#### Session 3: Many Models, One Theory
_Session Chair: Hengfeng Wei (Hunan University)_

[**Semantic Conformance of Concurrency Control Protocols under Mixed Isolation Levels**](http://arxiv.org/abs/2607.16696)  
_Qiuhuan Xiong (Nanjing University), Si Liu (Texas A&amp;M University), Hengfeng Wei (Hunan University), Yuxing Chen (Renmin University of China), Jidong Ge (Nanjing University)_

**[Polygraph: From Transaction Isolation Guarantees to Isolation Verification](papers/sccp26-polygraph.pdf)**  
_Jian Zhang (Northeastern University), Cheng Tan (Northeastern University)_

**[Reduce Once, Verify Many: Verifying Isolation Guarantees via Hierarchical Abstractions](papers/SCCP_2026_Ghasemirad_final.pdf)**  
_Shabnam Ghasemirad (ETH Zurich), Christoph Sprenger (ETH Zurich), Si Liu (Texas A&amp;M University), David Basin (ETH Zurich)_

#### Session 4: Consistency Goes Agentic
_Session Chair: Cheng Tan (Northeastern University)_

**[Notified Serializability: A Consistency Model for Concurrent LLM Agents](papers/sccp26-notified-serializability.pdf)**  
_Hongtao Lyu (Shanghai Jiao Tong University), Dingyan Zhang (Shanghai Jiao Tong University), Mingyu Wu (Shanghai Jiao Tong University), Xingda Wei (Shanghai Jiao Tong University), Haibo Chen (Shanghai Jiao Tong University)_

**[Beyond Pass Rate: A Hierarchy of Behavioral Consistency for LLM Agents](papers/sccp26-behavioral-consistency-llm-agents.pdf)**  
_Tian Lu (Northeastern University), Zikai Wang (Northeastern University), Cheng Tan (Northeastern University)_

---

[**AI-generated summaries of the accepted papers**](sccp26-paper-summaries.html)
&mdash; short overviews of all 10 papers, produced by an AI model and lightly
reviewed. Please refer to the papers above for authoritative descriptions.
