# Streamlit Learning

A set of small Streamlit exercises for practising Python and interactive web interfaces. The chapter files include examples such as a chai selector and a currency converter.

## What's here

- `Chapter-1.py` through `Chapter-5.py` — individual Streamlit exercises
- `chai_sales.csv` — sample data used by the exercises
- `AgeCalculator.py` — an empty placeholder
- `pyproject.toml` and `uv.lock` — project dependency information

## Run an exercise

The project specifies Python 3.13 or newer. Create an environment and install the dependencies needed by the exercise you want to run. For the first chapter:

```sh
python -m venv .venv
```

On Windows:

```powershell
.\.venv\Scripts\python.exe -m pip install streamlit
.\.venv\Scripts\python.exe -m streamlit run Chapter-1.py
```

The sales dashboard in `Chapter-4.py` also needs `pandas`. The currency converter in `Chapter-5.py` needs `requests` and an internet connection. Check each file's imports before running it.
