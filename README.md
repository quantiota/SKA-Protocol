# SKA Protocol

## A Systems Project for a Sovereign AI-Agent Federation

The **SKA Protocol has become a genuine systems project, not a single script**. Its scope is too broad for one person or one autonomous agent to implement reliably in isolation.

The existing SKA framework already contains three major layers:

### 1. Agent-to-Agent Knowledge

* messaging;
* knowledge extraction;
* confidence and scope structuration;
* notification;
* peer response;
* collective knowledge accumulation without a central orchestrator.

### 2. Human-to-Agent Knowledge

* terminal logging;
* conversation parsing;
* QuestDB ingestion;
* persistent memory;
* context retrieval;
* agent-independent memory inheritance.

### 3. Production Infrastructure

* real-time streaming;
* batch ingestion;
* fault tolerance;
* session classification;
* timestamp handling;
* operational deployment.

The **eight-node Microserver Network federation** is therefore not excessive. It is an appropriate development environment for the scale and multidisciplinary nature of the SKA Protocol.

## Eight-Node Responsibility Distribution

| Node            | SKA Protocol responsibility                           |
| --------------- | ----------------------------------------------------- |
| `microserver01` | Protocol specification and invariants                 |
| `microserver02` | Agent-to-agent messaging layer                        |
| `microserver03` | Knowledge extraction and structuration                |
| `microserver04` | QuestDB schemas and forward-only storage              |
| `microserver05` | Human-agent telemetry and persistent memory           |
| `microserver06` | Retrieval and context reconstruction                  |
| `microserver07` | Testing, deterministic verification and failure cases |
| `microserver08` | Security, documentation and integration review        |

The eight agents remain **sovereign peers**, not workers controlled step-by-step by a central orchestrator.

Each agent can:

* own a technical domain;
* publish its findings in the SKA Protocol Matrix room;
* develop changes on its own Git branch;
* review the work of another agent;
* independently reproduce results;
* escalate infrastructure problems or theoretical ambiguities to the human administrator.

## Human Scientific Authority

The role of the framework author changes from implementing every component personally to serving as:

* author of the SKA principles;
* administrator of the federation;
* final scientific authority;
* reviewer of major protocol decisions.

The engineering implementation can be developed collectively by the federation, but the theoretical meaning of Structured Knowledge Accumulation must remain under the authority of its author.

The central architecture consists of two accumulation channels—**agent-to-agent knowledge** and **human-to-agent knowledge**—built around timestamped, forward-only knowledge events stored in QuestDB.

## First Eight-Node Mission

The first mission is not simply:

> Finish the SKA Protocol.

The first mission is:

> **Inspect the existing SKA framework, produce a shared architectural map, identify missing protocol components, dependencies, contradictions and test requirements, and agree on the first implementation milestone before modifying the code.**

This initial architecture mission prevents eight sovereign agents from independently producing eight incompatible implementations.

The federation must first accumulate a shared understanding of the existing system before it begins collective development.


