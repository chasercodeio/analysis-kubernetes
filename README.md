# Analysis - Kubernetes

This repo serves as a code / knowledge dump of:
- Different CPU profiling applications (Pyroscope, OpenTelemetry eBPF profilers etc)
- Logging / Other metrics application (Grafana Loki, Mimir, etc)

All working in Kubernetes. It will be mostly for testing different applications and the pipeline they use, from grabbing relevant data to displaying it.

## Currently working:

### CPU profiling

- Pyroscope Alloy -> Pyroscope - UI
- Pyroscope (Server + UI) ?
- OpenTelemetry profiler -> OpenTelemetry Collector (Just as a collector) -> Pyroscope UI
- OpenTelemetry profiler -> OpenTelemetry Collector (with Symbolization) -> Pyroscope UI


Each pipeline will have their own subdirectory under `profilers` root directory

### Logging and other Metrics applications

- Grafana (Dashboard UI)
- Promethius
- Grafana Loki
- Will add more as I make it work


