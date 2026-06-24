# Keith Hetrick

I build correctness-critical systems. Two of them right now: real-time audio
plugins, and a governed context backend that AI agents read from over MCP,
read-only and approval-gated. Founder and Lead Engineer at
[Bellweather Studios](https://www.bellweatherstudios.com).

I spent a decade making records before building the tools for it.
Grammy-nominated, a few billion streams, a Billboard #1. The audio work is an
extension of having done the job.

### Bellweather Audio Core

A snapshot out of the Bellweather ecosystem, now open source. It's
framework-neutral C++, built around a from-scratch loudness meter
(BS.1770 / EBU R128) with a conformance suite you can run yourself.

[github.com/keithhetrick/bellweather-audio-core](https://github.com/keithhetrick/bellweather-audio-core) · [bellweatherstudios.com/bellweather-audio-core](https://www.bellweatherstudios.com/bellweather-audio-core)

### The rest of it

Real-time audio: native C++20 plugins across VST3, AU, AAX, CLAP. Lock-free,
and nothing gets allocated on the audio thread.

Governed context backend: Prisma/Postgres systems of record that are the single
source of truth for clients, human and machine. Authority is data, not
inference. Every mutation is audited. OAuth on MCP, in production.

Platform: the build and test infrastructure that keeps all of it honest. Drift
gates, shared kernels, and far too many tests.

### Links

[Resume](https://www.bellweatherstudios.com/resume) · [Engineering](https://www.bellweatherstudios.com/engineering) · [Bellweather Studios](https://bellweatherstudios.com) · [Cupola](https://cupola.bellweatherstudios.com)
