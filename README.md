# python-docker
```shell
docker build . -t python:tushare
docker run --rm -it python:tushare bash
```

```python
import tushare as ts
ts.get_k_data('399300', index=True,start='2016-10-01', end='2016-10-31')
```
