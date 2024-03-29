# \[Work In Progress\] AMWA BCP-006-02: NMOS With H.264

[![Lint Status](https://github.com/AMWA-TV/bcp-006-02/workflows/Lint/badge.svg)](https://github.com/AMWA-TV/bcp-006-02/actions?query=workflow%3ALint)
[![Render Status](https://github.com/AMWA-TV/bcp-006-02/workflows/Render/badge.svg)](https://github.com/AMWA-TV/bcp-006-02/actions?query=workflow%3ARender)

This repository holds the source for this Specification, part of the family of [Networked Media Open Specifications](https://specs.amwa.tv/nmos) from the [Advanced Media Workflow Association](https://amwa.tv)

<!-- INTRO-START -->

### What does it do?

- Enables Registration, Discovery, and Connection Management of H.264 Endpoints using the AMWA IS-04, IS-05 and IS-11 NMOS Specifications.

### Why does it matter?

- It helps ensure consistency between implementations offering NMOS control for H.264 endpoints.

### How does it work?

- It specifies what resources and attributes MUST be provided when using NMOS with [H.264][] streams.
- It specifies requirements for SDP when it is used with a transport supporting SDP transport files.
- It provides examples of how to use IS-04, IS-05 and IS-11 in the context of H.264 streams - specifically H.264 encapsulated in RTP as described in IETF [RFC 6184][RFC-6184]. It also describe to some extent how to use H.264 with RTP and other transports that encapsulate the H.264 video streams in an MPEG2-TS transport stream.

<!-- INTRO-END -->

## Getting started

There is more information about the NMOS Specifications and their GitHub repos at <https://specs.amwa.tv/nmos>.

[H.264]: https://www.itu.int/rec/T-REC-H.264 "Advanced video coding for generic audiovisual services"
[RFC-6184]: https://tools.ietf.org/html/rfc6184 "RTP Payload Format for H.264 Video"
