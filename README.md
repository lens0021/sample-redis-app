redis-sample-app
========
Sample web server using Redis to test [Nomad]

```bash
python3 -m venv .venv
. .venv/bin/activate
pip install -U pip setuptools
pip install -r requirements.txt

flask run
```

[Nomad]: https://www.nomadproject.io/
