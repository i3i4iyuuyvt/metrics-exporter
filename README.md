# metrics-exporter

A minimal metrics registry with counters, gauges and histograms.

## Why

Written while learning the language properly, and kept because it still works.

## Install

```bash
pip install metrics-exporter
```

## Usage

```python
from metrics_exporter import metricsExporter

result = metricsExporter("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
