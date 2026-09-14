<div align="center">

# Project Sandstar

**Source-available building automation controls.**
Hardware-agnostic control engines, web tools for Sedona and SkySpark, and AI tooling for the people who keep buildings running.

[![Website](https://img.shields.io/badge/project--sandstar.org-website-0a7cff?style=flat-square)](https://www.project-sandstar.org)
[![Wiki](https://img.shields.io/badge/wiki-docs%20%26%20training-6b7280?style=flat-square)](https://wiki.project-sandstar.org)
[![Membership](https://img.shields.io/badge/join-membership-16a34a?style=flat-square)](https://membership.project-sandstar.org/register)
[![Haystack](https://img.shields.io/badge/Project-Haystack-f59e0b?style=flat-square)](https://project-haystack.org)
[![Sedona](https://img.shields.io/badge/Sedona-Framework-8b5cf6?style=flat-square)](https://www.project-sandstar.org/projects)

</div>

---

## Who we are

Project Sandstar is run by **Kum Yıldızı Derneği** (Sandstar Association), a non-profit based in Fethiye, Türkiye. The association exists to develop and spread open, flexible, and sustainable solutions for building automation and IoT, so that controllers from different manufacturers can work together without vendor lock-in.

Our stack sits on two open standards:

- **[Sedona Framework](https://www.project-sandstar.org/projects)** for portable, component-based control logic that runs on small embedded hardware.
- **[Project Haystack](https://project-haystack.org)** for semantic tagging so data from any device means the same thing everywhere.

The engine is open source. The applications built on top of it ship under the [Project Sandstar Source-Available License (PSSL v1.1)](https://www.project-sandstar.org/license): free on unlimited devices when the data comes from Sandstar controllers, with a commercial arrangement for data from other systems.

## Repositories

| Repository | What it is | Stack |
|---|---|---|
| [**Sandstar_Rust**](https://github.com/Project-SandStar/Sandstar_Rust) | The Sandstar Engine: a pure-Rust IoT/HVAC control engine for BeagleBone. Channel-based I/O, PID loops and sequencers, BACnet/IP and MQTT drivers, Haystack REST + WebSocket APIs, and an in-process Sedona VM with zero C/FFI. Live in production. | Rust · ARM · BACnet · MQTT · Haystack |
| [**AxonMcpServer**](https://github.com/Project-SandStar/AxonMcpServer) | An MCP (Model Context Protocol) server that indexes Axon code and docs for SkySpark, so AI assistants can discover HVAC sequences, fault-detection sparks, energy reports and workflows. Includes a VS Code extension and a dashboard. | TypeScript · MCP · SkySpark · Axon |
| [**SideCar**](https://github.com/Project-SandStar/SideCar) | A GPU orchestrator agent for LLM workloads. Run it on a machine with a GPU and let remote apps use it for embeddings, completions, OCR and reranking, with honest VRAM accounting and no silent CPU fallback. | TypeScript · Ollama · vLLM · Docker |

Web tools such as the **Sandstar Web Editor**, **Sandstar Web Socket** and **Sandstar Port Manager** are described on the [projects page](https://www.project-sandstar.org/projects).

## Get involved

- **Use it.** Start with the [wiki](https://wiki.project-sandstar.org) for docs, tutorials and training material.
- **Contribute.** Open an issue or pull request on any repository above.
- **Join.** [Personal and corporate memberships](https://membership.project-sandstar.org/register) fund the association and unlock training, the community forum and priority support.
- **Talk to us.** Use the [contact form](https://www.project-sandstar.org/contact) or the [community forum](https://www.project-sandstar.org/forum).

<div align="center">
<sub>Kum Yıldızı Derneği · Fethiye, Türkiye · <a href="https://www.project-sandstar.org">project-sandstar.org</a></sub>
</div>
