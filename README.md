# Instruksi Instalasi Library

## Menggunakan pip

1. Buat virtual environment:
   ```bash
   python -m venv .venv
   ```

2. Aktifkan virtual environment:
   - Windows:
     ```bash
     .venv\Scripts\activate
     ```
   - Mac/Linux:
     ```bash
     source .venv/bin/activate
     ```

3. Install dependensi dari `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

## Menggunakan UV

Jika Anda menggunakan [uv](https://github.com/astral-sh/uv):

```bash
uv sync
```
