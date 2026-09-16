# High-Level Quantum Circuit Synthesis Toolkit

<p align="center">
  <img src="logos/toolkit.svg" width="840" alt="The Q-HLS weather logo family: typhoon, lightning, frost, dawn, and sampled typhoon">
</p>

**Q-HLS** brings together tools, libraries, and benchmarks for logic synthesis,
quantum state preparation, T-count optimization, and lattice-surgery compilation.
This repository is the toolkit's project directory and home for its shared
visual identity. Each project maintains its own implementation, installation
instructions, examples, and license.

## Projects

| | Project | Area | What it does | Get started |
| :---: | --- | --- | --- | --- |
| <a href="https://github.com/Nozidoali/lut-synth"><img src="logos/lut-synth.svg" width="72" height="72" alt="lut-synth logo"></a> | **[lut-synth](https://github.com/Nozidoali/lut-synth)**<br>`lut-synth` | Logic synthesis | Truth-table logic synthesis and exact or approximate XAG optimization. | [README](https://github.com/Nozidoali/lut-synth#readme) |
| <a href="https://github.com/Nozidoali/MiniFlash"><img src="logos/miniflash.svg" width="72" height="72" alt="MiniFlash logo"></a> | **[MiniFlash](https://github.com/Nozidoali/MiniFlash)**<br>`MiniFlash` | Lattice surgery | Clifford+T compilation into 3D lattice-surgery layouts with glTF output. | [README](https://github.com/Nozidoali/MiniFlash#readme) |
| <a href="https://github.com/Nozidoali/exact-t-map"><img src="logos/exact-t-map.svg" width="72" height="72" alt="Exact T Map logo"></a> | **[Exact T Map](https://github.com/Nozidoali/exact-t-map)**<br>`exact-t-map` | Exact synthesis | Clifford+T technology mapping for XAG networks using an exact T library. | [README](https://github.com/Nozidoali/exact-t-map#readme) |
| <a href="https://github.com/Nozidoali/oracle-synth"><img src="logos/oracle-synth.svg" width="72" height="72" alt="Oracle Synth logo"></a> | **[Oracle Synth](https://github.com/Nozidoali/oracle-synth)**<br>`oracle-synth` | State preparation | Quantum state preparation using rotation-based and QROM-based circuit synthesis. | [README](https://github.com/Nozidoali/oracle-synth#readme) |
| <a href="https://github.com/Nozidoali/qlut-benchmarks"><img src="logos/qlut-benchmarks.svg" width="72" height="72" alt="QLUT Benchmarks logo"></a> | **[QLUT Benchmarks](https://github.com/Nozidoali/qlut-benchmarks)**<br>`qlut-benchmarks` | Benchmarks | Truth tables, quantum circuits, and metadata for synthesis experiments. | [README](https://github.com/Nozidoali/qlut-benchmarks#readme) |

`lut-synth` is the QLUT logic-synthesis component. The state-preparation project
is published as `oracle-synth`; its earlier development repository is
[qsp-compilation](https://github.com/Nozidoali/qsp-compilation).

## Where to start

- **Synthesize or optimize Boolean logic:** start with `lut-synth`; use
  `qlut-benchmarks` for truth tables and circuit-generation workloads.
- **Prepare a quantum state:** start with `oracle-synth` for rotation-based and
  QROM-based methods that emit OpenQASM circuits.
- **Map XAG networks to Clifford+T circuits:** start with `exact-t-map`, which
  uses an exact T library for technology mapping.
- **Compile to lattice surgery:** start with `MiniFlash` for Clifford+T
  compilation into 3D spacetime layouts that can be exported as glTF scenes.

These are complementary research projects with their own interfaces. Follow
each project's README for supported inputs, dependencies, and reproducible
examples.
