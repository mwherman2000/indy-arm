# indy-arm - Hyperledger Indy/Sovrin Comprehensive Architecture Reference Model (INDY ARM)
_Draft document for discussion purposes_

Michael Herman (Toronto/Calgary/Seattle)
Hyperonomy Business Blockchain Project / Parallelspace Corporation
January 2019

Update cycle: As required – sometimes several times in a single day.

# Overview

The purpose of the Hyperledger Indy/Sovrin (Indy) Comprehensive Architecture Reference Model (INDY ARM) is to provide a complete, reliable, precise, visual reference for the concepts presented in the draft Decentralized Identifiers (DIDs) specification (link).

The primary audience for this article are: software people (software architects and developers), enterprise architects, and anyone new to the Hyperledger Indy project or the field of self-sovereign identity (SSI) looking to find a fast on-ramp.

# Goals 

The goals of the INDY ARM are:

- Create a complete, reliable, precise, visual model depicting Decentralized Identifiers (DIDs), DID Entities, DID Documents, and the companion Hyperledger Indy ecosystem of software projects, software components, and data elements.
- Enable software people to become more knowledge about and productive with the Hyperledger Indy software platform (and Sovrin governance framework) as quickly and as easily as possible.
- Provide a common language of discourse for describing the current state architecture as well as potential future state architectures for the Indy ecosystem and community (with particular focus emphasis on the needs and requirements of software people).

## Principles

The guiding principles for the INDY ARM are:

- Provide reliable documentation: timely, accurate, visual, and complete
- Save as much of a software person’s time as possible
- Leverage open source modeling specifications and tools like ArchiMate and Archi, respectively
- Leverage enterprise architecture concepts to explain Decentralized Identifiers and Entities in a way doesn’t detract from the adoption of the INDY ARM

## Drivers

The drivers for the INDY ARM are:

- The initial driver for the INDY ARM is the create a reference model to help correct a series of issues found in the draft DID specification and documented in the project’s GitHub issues list (Fall 2018).

NOTE: Some of the elements depicted in the INDY ARM have been influenced by the Verified Credentials project – particularly, the business roles and processes in the Business Layer (1), the Local Ledger State (17) in the Technology Layer – Data Model (15), and the Credential Registry Agent Node (39) in the Technology Layer (30).

## Companion Articles

- What is a DID?
- INDY ARM In Practice: End-to-end Path from id (DID) to a Real-Life Something
- Vision: Trusted Digital Web

## Tooling

- ArchiMate Modeling Specification: The Open Group ArchiMate 3.0 Specification
- Archi Modeling Tool: Archi, the open source ArchiMate modeling platform

## Recent Feedback and Changes

Ledger Agent Node changed to Ledger Node (@danielhardman)
Ledger Nodes: A2A Protocol corrected to Ledger-to-Ledger Protocol (@danielhardman)
Relationships added to depict A2A Protocol messaging between Edge Agents and Cloud Agents (@danielhardman)
(“Identity” Layer) appended to Business Layer – Architecture (@mwherman2000)
(“Edge” Layer) appended to Application Layer – Architecture (@mwherman2000)
(“Cloud” and “Ledger” Layers) appended to Technology Layer – Architecture (@mwherman)
Owner changed to Controller in (P2) (per CCG discussion Jan. 15 2019)
Principle P7 added. See #4.
Non-Fungible Entities added to Principles. (P8) and (P9) added. (P1) updated.
Element (3) is now shown as copies of the same (3a) and (3b).
“inanimate thing” changed to Non-Fungible Entity (10).
Principle P4 reworded. DID Entity (14) redefined.
Indy Ledger Local Node State changed to Indy Ledger Local Node State (Replica) (36) and (38).
Indy Ledger (Journal) changed to Indy Ledger Local State (17).
Indy Transactions changed to Indy Transactions (Journal) (17).
Removed DID Resolver Full Node (@peacemaker).
Four perspectives added to the both of the ARM.
Indy Ledger Local Node State (Replica) was changed to Local Ledger State (Replica).
Partitioned the DID Data Model (old 12) perspective into DID Document Data Model (44) and DID Data Model (new 12) perspectives.
Added elements (44) to (50) to support change 19.

## Architecture Perspectives 

Horizontally, the INDY ARM is partitioned into 4 perspectives:

- Projects and Distributions (A)
- Ecosystem Architecture (B)
- DID Data Model (C)
- DID Document Data Model (D)
- [Verified Credentials (VC) Data Model (Future)]
- Principles (E)

## Architecture Domains

Vertically, the INDY ARM is divided into 3 architecture domains that span the 4 perspectives:

- Business Layer (1) and (8)
- Applications Layer (23), (44), and (12)
- Technology Layer (30), (49), and (15)

Viewpoints

The INDY ARM is illustrated in the following “all in” viewpoint. The INDY ARM is an actual queryable model – it is not a drawing (e.g. a Visio or PowerPoint diagram).

The Narration section that follows the graphic includes a description of each of the numbered bullets.

Click on the graphic to enlarge it in a separate browser tab.  Suggestion: Drag the new browser tab onto a second monitor if you have one.

