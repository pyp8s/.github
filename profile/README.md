<br>
<h1 align="center">
  😺 Prometheus metrics for your application 😸
  <br>
  <br>
</h1>

<br>

```python
from pyp8s import MetricsHandler

MetricsHandler.init("events_total", "counter", "Events happening")
MetricsHandler.inc("events_total", 1, source="around", kind="good")

MetricsHandler.serve()
```

<div align="center"> ↓ ↓ ↓ </div>
<br>


```python
# HELP events_total Events happening
# TYPE events_total counter
events_total{source="around",kind="good"} 1
```

<h1>&nbsp</h1>
<br>

<p>
  <div>
    Latest: <a href="https://github.com/pyp8s/pyp8s/releases/latest" target="_blank">https://github.com/pyp8s/pyp8s/releases/latest</a>
  </div>

<div>
    Examples: <a href="https://github.com/pyp8s/examples" target="_blank">https://github.com/pyp8s/examples</a>
  </div>
  
  <div>
    PyPi: <a href="https://pypi.org/project/pyp8s/" target="_blank">https://pypi.org/project/pyp8s/</a>
  </div>

</p>

<p align="right">
  <span title="a tiny cock on your right">
    🐓
  </span>
</p>
