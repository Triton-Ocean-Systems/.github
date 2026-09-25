<p align="center">
  <img src="banner.png.png" alt="Triton Ocean Systems: building the distributed intelligence layer for the ocean" width="100%">
</p>

<p align="center">
  <b>Persistent, low-cost ocean observation. One network. One operating picture.</b>
</p>

---

## About us

The ocean is severely under-observed. Sensing is expensive, sensors are isolated, and the data that does get collected is fragmented across incompatible systems and dashboards.

**Triton Ocean Systems** is building the infrastructure to change that: standardized, modular sensing nodes deployed along coastlines, on vessels and offshore, connected to a single software platform that turns raw telemetry into operational intelligence.

We are an early-stage company based in South Florida, starting with coastal deployments along Florida's Gulf and Atlantic coasts.

## What we're building

| | |
|---|---|
| **Triton SEAVANT** | Ocean-intelligence operator console. A single geospatial operating picture across Triton nodes and external feeds: nodes, vessel traffic, environmental conditions, alerts and history. |
| **Triton Nodes** | A modular hardware family built on commercial sensors and compute. **BeachNode** for coastlines, marinas and ports. **OceanNode** for offshore stations. **SailNode** to turn vessels into mobile observation platforms. **Ocean Node 001**, our first reference prototype, is in active development. |
| **Edge + Comms** | On-node inference, event-driven sensing and smart transmission over cellular, LoRa, mesh and satellite, so only what matters leaves the node. |
| **Triton Coastal** | Our first application: coastal intelligence for Florida communities, starting with sargassum monitoring and response planning. |

## How it fits together

```mermaid
flowchart LR
    subgraph Field["In the water"]
        B["BeachNode"]
        O["OceanNode"]
        S["SailNode"]
    end
    E["Edge processing<br/>detect, compress, prioritize"]
    C["Multi-path comms<br/>cellular, LoRa, mesh, satellite"]
    P["Triton platform<br/>normalize, store, correlate"]
    X["External feeds<br/>AIS, NOAA, NWS"]
    V["Triton SEAVANT<br/>operator console"]
    A["Partner APIs<br/>open schemas"]
    B --> E
    O --> E
    S --> E
    E --> C --> P
    X --> P
    P --> V
    P --> A
```

## Where we are

- **Now:** building and bench-validating Ocean Node 001, our reference prototype, and developing Triton SEAVANT.
- **Next:** first field deployment in South Florida, then paid pilots with coastal operators.
- **Open work:** we publish our data formats openly, starting with the [Triton Observation Schema](https://github.com/Triton-Ocean-Systems/triton-observation-schema).

## Principles

- **Persistent, not periodic.** Continuous observation catches change early.
- **Edge first.** Process locally, transmit what matters.
- **Open interfaces.** Common schemas and APIs so data isn't trapped.
- **Trustworthy data.** Node identity, timestamps, geolocation, calibration metadata and lineage on every observation.
- **Modular by design.** Sensors, radios and compute are independently replaceable.

## Repositories

| Repository | |
|---|---|
| [**triton-observation-schema**](https://github.com/Triton-Ocean-Systems/triton-observation-schema) | Open JSON Schema for ocean observation records with built-in provenance. Public, Apache-2.0. |

Our core platform, hardware and autonomy repositories (SEAVANT, Ocean Node 001 and its autonomy stack) are private while in active development. Access for partners and investors is available on request.

## Work with us

- **Coastal operators, counties and marinas:** interested in a pilot deployment.
- **Researchers and agencies:** interested in data partnerships or shared infrastructure.
- **Investors:** interested in the company and our roadmap.

Reach us at **tritonminingco@gmail.com**.

<p>
  <a href="https://www.instagram.com/tritonoceansystems"><img src="https://img.shields.io/badge/Instagram-tritonoceansystems-0a2a43?logo=instagram&logoColor=white" alt="Instagram"></a>
  <a href="https://www.youtube.com/@TritonMiningCo"><img src="https://img.shields.io/badge/YouTube-Triton-0a2a43?logo=youtube&logoColor=white" alt="YouTube"></a>
</p>

<sub>© Triton Ocean Systems. All rights reserved.</sub>
