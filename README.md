<div align="center">
    <img width="120px" height="auto" src="https://raw.githubusercontent.com/jamesgober/jamesgober/main/media/icons/hexagon-3.svg" alt="Triple Hexagon">
    <h1>
        <strong>RUST</strong>
        <sup>
            <br>
            <sub>HIGH-PERFORMANCE LIBRARY COLLECTION</sub>
            <br>
        </sup>
    </h1>
</div>

The JG Rust Collection. Libraries, modules, and tools built for performance-critical systems. All projects follow **REPS** (Rust Efficiency & Performance Standards) — zero-cost abstractions, minimal allocations, lock-free where possible.

---

## Libraries (lib)

Reusable library crates. Import as dependencies.

| Crate | Description |
|-------|-------------|
| [metrics-lib](https://github.com/jamesgober/metrics-lib) | Lock-free metrics. 0.6ns gauges, 18ns counters, timers, rate meters, adaptive sampling, system health. |
| [error-forge](https://github.com/jamesgober/error-forge) | Structured error framework. Typed errors with macros, contextual metadata, severities, recovery helpers. |
| [rust-benchmark](https://github.com/jamesgober/rust-benchmark) | Benchmarking library. Dev mode profiling, prod mode monitoring with <10ns overhead, regression alerts. |
| [network-protocol](https://github.com/jamesgober/network-protocol) | Protocol layer for local, remote, and cluster communication. Built for databases, daemons, real-time systems. |

## Processes (proc)

Standalone daemon and service frameworks.

| Crate | Description |
|-------|-------------|
| [proc-daemon](https://github.com/jamesgober/proc-daemon) | Cross-platform daemon framework. Async-native, graceful shutdown, production-grade service lifecycle. |

## Modules (mod)

Modular components and frameworks.

| Crate | Description |
|-------|-------------|
| [mod-cli](https://github.com/jamesgober/mod-cli) | CLI framework. Modular command parsing, customizable output, built for speed and control. |

---

## REPS — Rust Efficiency & Performance Standards

Every project in this collection is built to REPS. The standard defines expectations for:

- **Zero-cost abstractions** — no runtime overhead for type safety or API design
- **Minimal allocations** — stack-first, pool when needed, heap as last resort
- **Lock-free concurrency** — atomics over mutexes on hot paths
- **Predictable latency** — no hidden GC pauses, no unbounded allocations
- **Minimal dependencies** — fewer deps = fewer supply chain risks, faster builds
- **Benchmarked claims** — if you say it's fast, prove it with numbers

Full REPS documentation: [GUIDELINES.md](GUIDELINES.md)

---

## Author

James Gober — [github.com/jamesgober](https://github.com/jamesgober)
