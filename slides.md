---
title: JAM Status
theme: seriph
layout: intro
favicon: ./assets/favicon.png
transition: slide-left
---

# JAM Status Update

TRAM, @0trust3r

<style>
.slidev-layout{
  background-image: url("/assets/background.png");
  background-size: cover;
}
</style>

---
layout: left
---

# Contents

1. Hello World
2. Development Journey
3. TRAM
4. TVM
5. Roadmap
6. Alignment
7. Q&A

<style>
.slidev-layout{
  background-image: url("/assets/background.png");
  background-size: cover;
}
</style>

---
layout: section
---
# Hello World!

<style>
.slidev-layout{
  background-image: url("/assets/background.png");
  background-size: cover;
}
</style>
---
layout: section
---
# Development Journey

<style>
.slidev-layout{
  background-image: url("/assets/background.png");
  background-size: cover;
}
</style>

---
layout: two-cols
---

# Months 1-2
- GP Exploration

- Block Serialization

- VRF Bindings

- Data Structures

- Safrole

::right::

# Month 3
- Decouple STF

- STF components *(reports, assurances, disputes, preimages, authorizations, history, statistics)*

- PVM Exploration

<style>
.slidev-layout{
  background-image: url("/assets/background.png");
  background-size: cover;
}
</style>

<!--
decouple
- types <-> DB
- validations <-> updates

recompiler
- appendix A
-->

---
layout: two-cols
---

# Month 4
- PVM recompiler
  - Single-pass
  - No host function support


::right::

# Month 5
- Host functions
- Revisit in-mem DB & state cache architecture
- PVM account cache traits
- Accumulation functions



<style>
.slidev-layout{
  background-image: url("/assets/background.png");
  background-size: cover;
}
</style>

<!--
decouple
- types <-> DB
- validations <-> updates

recompiler
- appendix A

host functions
- general
- accumulate (some)
-->

---
layout: left
---

# Month 6
- Refactor VRF Bindings
- JAM big-picture review


<style>
.slidev-layout{
  background-image: url("/assets/background.png");
  background-size: cover;
}
</style>

---
layout: section
---

# TRAM

<style>
.slidev-layout{
  background-image: url("/assets/background.png");
  background-size: cover;
}
</style>

---
layout: left
---

# Architecture
- Python
- Service-oriented concurrency
- Operating Modes

<br />

# Status
- Pre-M1

<br />

# Available Tools

- Python library for vrf verification `jam-vrf`


<style>
.slidev-layout{
  background-image: url("/assets/background.png");
  background-size: cover;
}
</style>

---
layout: section
---

# TVM

<style>
.slidev-layout{
  background-image: url("/assets/background.png");
  background-size: cover;
}
</style>

---
layout: left
---

# Architecture
- Rust
- Assembler & Runtime
- JIT Assembly
- Obsessively Minimized memory IO
- Implementation-agnostic API

<br />

# Status
- Pre-release
- Passing PVM testvectors
- Host function testvectors *in-progress*

<br />

# Available Tools

- Early-preview API Docs


<style>
.slidev-layout{
  background-image: url("/assets/background.png");
  background-size: cover;
}
</style>

---
layout: iframe
url: https://zero-trust-collective.github.io/tvm/tvm_runtime/traits/index.html
---

---
layout: section
---

# Roadmap

<style>
.slidev-layout{
  background-image: url("/assets/background.png");
  background-size: cover;
}
</style>

---
layout: two-cols
---

# May
- Implement TVM traits for TRAM
- Perf testing famework

<br />

# June
- M1 compliance
- TVM optimizations

<br />

# July...
- Networking
- Secrets
- Refinement
- Auditing

::right::

<img border="rounded" src="/assets/tracers.png" alt="">

<style>
.slidev-layout{
  background-image: url("/assets/background.png");
  background-size: cover;
}
</style>

<!--
M1 compliance
- fill in host fns & stf gaps
-->

---
layout: section
---

# Alignment

Decentralize, Decentralize, Decentralize


<style>
.slidev-layout{
  background-image: url("/assets/background.png");
  background-size: cover;
}
</style>

---
layout: left
---

# Approach
- Entrepreneurship
- Research
- Public goods

<br />

# Values
- Less trust, more truth
- Equal digital agency for all

<style>
.slidev-layout{
  background-image: url("/assets/background.png");
  background-size: cover;
}
</style>


---
layout: section
---

# Q&A

<style>
.slidev-layout{
  background-image: url("/assets/background.png");
  background-size: cover;
}
</style>


---


<img border="rounded" src="/assets/qr.png" alt="">




<style>
.slidev-layout{
  background-image: url("/assets/background.png");
  background-size: cover;
}
</style>
