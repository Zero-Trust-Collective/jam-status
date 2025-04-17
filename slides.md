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
# Month 1
- Study GP
- Block Serialization

::right::

# Month 2
- VRF Python Bindings
- Data Structures
- Safrole


<style>
.slidev-layout{
  background-image: url("/assets/background.png");
  background-size: cover;
}
</style>


---
layout: two-cols
---
# Month 3
- [refactor] stf (move away from redis-om to bytes-native)
- [refactor] stf (decouple component validations from updates)
- [stf] reports, assurances, disputes, preimages, authorizations, history, statistics
- pvm planning

::right::

# Month 4
- pvm recompiler (basic, no host functions) (appendix A) (passing koute testvectors)


<style>
.slidev-layout{
  background-image: url("/assets/background.png");
  background-size: cover;
}
</style>

---
layout: two-cols
---
# Month 5
- [refactor] pvm (distinct crates for assembler & runtime)
- general host functions (all)
- accumulate host functions (some)
- revisit in-mem DB & state cache architecture
- [refactor] stf (fully decouple component validations from updates, in-mem db becomes first class citizen, testbench)
- account cache traits
- accumulate invocation functions

::right::

# Month 6
- [refactor] vrf bindings lib (going public)
- re-read GP, step back to see the forest
- prepare for Lisbon


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
- Passing Koute testvectors
- Host function testvectors *in-progress*
- Mock trait implementations for testvectors

<br />

# Available Tools

- Pre-release API Docs


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
layout: section
---

# Alignment

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

links: this presentation, jam-vrf, tvm docs, gh org

<style>
.slidev-layout{
  background-image: url("/assets/background.png");
  background-size: cover;
}
</style>
