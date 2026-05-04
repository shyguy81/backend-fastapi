
# lancer manuellement

```bash
python3 -m virtualenv --always-copy .venv
source .venv/bin/activate
pip install -r requirements.txt
#
uvicorn main:app --host 0.0.0.0 --port 8000 --reload
```