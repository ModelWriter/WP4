Work Package 4
===
**Work Package 4 - Knowledge Base Design and Implementation (Mantis)**

[`Product Backlog of WP7`](https://waffle.io/ModelWriter/WP4)

The product backlog itself is implemented in the [`issue tracker`](https://github.com/modelwriter/wp4/issues) of this repository

Objectives
---

The primary objective of this WP is to provide the Knowledge Base component (data structures and services) of the ModelWriter platform.

**This objective is broken down into the following sub-objectives**

 * To design and implement the ModelWriter’s federated Knowledge Base itself, hosting multiple formalisms. 
 * To design and implement its bi-directional text-model synchronization mechanism.
 * To design and implement its API.
 * To design and implement a set of specialised modules `(plug-ins)` that exploit the Knowledge Base in ways that make the tasks of Technical Authors much more productive, e.g. consistency checks.
 * To design and implement the collaborative functions linking and hierarchically organizing multiple ModelWriter KBs used by different Technical Authors on different sites.

Expected Results
---

 * A Federated Knowledge Base and its API.
 * The **Intent**-based bi-directional synchronization mechanism (between text and models within a KB).
 * An initial set of plug-ins providing high added value services.
   * `Plug-in #1` – This provides consistency and completeness checks within the same software lifecycle document, allowing automatic quality review of the content (meaning).
   * `Plug-in #2` – This provides consistency and completeness checks between related set of documents and incl. check for compliance to a software engineering standard (such as the ECSS-E-ST-40C used in the space industry).
   * `Plug-in #3` – This provides semantic comparison between two versions of the same software lifecycle document (i.e. what conceptual changes have happened).
 * The synchronization mechanism organizing a hierarchy of distributed & collaborating Technical Authors.

