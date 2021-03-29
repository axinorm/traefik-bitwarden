# Traefik mTLS

## Generate docker compose file

Install jinja2

```sh
virtualenv .venv
source .venv/bin/activate
pip install jinja2
```

Set environment variables

```sh
export TB_SERV_OS=linux
export TB_SERV_ARCH=arm
export TB_URL_TRAEFIK=admin.example.com
```

Generate file

```python
python3 generate_compose_file.py
```