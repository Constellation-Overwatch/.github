# Welcome 🛰️

Constellation Overwatch is the open-source C4ISR data fabric to power your autonomous fleet management dreams. The most efficient way to build tactical awareness systems for drones, aircraft, robots, and everything in between.

<p align="center">
  <img src="https://constellation-overwatch.github.io/public/overwatch.svg" alt="Constellation Overwatch" width="800"/>
</p>

### Constellation Overwatch Core

A distributed command and control system that goes anywhere. Edge, cloud, or hybrid &mdash; **the next evolution of autonomous fleet coordination.**

- **Real-time Telemetry** &mdash; Native MAVLink protocol support with NATS JetStream for durable streaming workflows.
- **Edge Intelligence** &mdash; Modern object detection with RT-DETR and Moondream for tactical awareness.
- **Hierarchical Mesh** &mdash; Multi-org, multi-entity pub/sub architecture without conflicts.
- **Video Integration** &mdash; Out of the box RTSP/HTTP video streaming with MediaMTX and FFmpeg.
- **MAVLink Compatible** &mdash; Fully backwards compatible with PX4/ArduPilot, but built for autonomous swarms.
- **Open Contribution** &mdash; Take your seat at the table and contribute to the future of autonomous C4ISR.

Get started with Constellation Overwatch:

```bash
git clone https://github.com/Constellation-Overwatch/constellation-overwatch.git
go run ./cmd/microlith/main.go
```

Get started with our edge components:

- [MAVLink Bridge](https://github.com/Constellation-Overwatch/mavlink2constellation) &mdash; Serial/UDP to NATS routing
- [Object Detection](https://github.com/Constellation-Overwatch/overwatch-obj-detection) &mdash; RT-DETR and Moondream inference
- [Web Dashboard](https://github.com/Constellation-Overwatch/constellation-overwatch) &mdash; Real-time fleet monitoring
- [Mobile Apps](https://github.com/Constellation-Overwatch) &mdash; Tactical control interfaces
- [CLI Tools](https://github.com/Constellation-Overwatch) &mdash; Command line fleet management

### Constellation Cloud

Deploy unlimited autonomous fleets in production environments. Edge-to-cloud synchronization.

- **Multi-Platform Support** &mdash; Aircraft, drones, robots, and amphibious systems with unified telemetry.
- **Durable Streams** &mdash; Keep devices synchronized with NATS JetStream persistence and replay.
- **Tactical Analytics** &mdash; Monitor performance, detect anomalies, and track mission objectives.
- **Fleet Coordination** &mdash; Collaborative autonomous operations with hierarchical command structure.
- **Video Intelligence** &mdash; Real-time object detection and situational awareness integration.
- **Self-Hosted Ready** &mdash; Deploy on your infrastructure with full control and security.

Get started with Constellation deployment:

- [Quickstart Guide](https://constellation-overwatch.github.io/) &mdash; Deploy in minutes!
- [API Reference](https://github.com/Constellation-Overwatch/constellation-overwatch/blob/main/docs/api.md) &mdash; Manage organizations and entities programmatically.
- [Edge Setup](https://github.com/Constellation-Overwatch/mavlink2constellation#readme) &mdash; Connect your vehicles and sensors.
- [Detection Pipeline](https://github.com/Constellation-Overwatch/overwatch-obj-detection#readme) &mdash; Configure computer vision workflows.

### Supported Platforms

Join the autonomous revolution across multiple domains:

- **✈️ Aircraft** &mdash; Fixed-wing, eVTOL, airships with PX4/ArduPilot integration
- **🚁 Drones** &mdash; Class 1-3 multirotors, hexacopters, swing-wing configurations  
- **🦾 Robots** &mdash; Humanoids, quadrupeds, amphibious systems with sensor fusion
- **📡 Edge Systems** &mdash; RTSP cameras, USB sensors, serial devices via unified fabric

### Community

Join the Constellation Overwatch community to collaborate on autonomous systems, share tactical insights, and discuss best practices on [GitHub Discussions](https://github.com/orgs/Constellation-Overwatch/discussions), [Discord](https://discord.gg/constellation), and [LinkedIn](https://linkedin.com/company/constellation-overwatch).