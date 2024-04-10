# Multilingual-AI-Assistant

## How to run?
## STEPS:
Clone the repository

### Project repo: https://github.com/AIWalaBro/Multilingual-AI-Assistant


## STEP 01- Create a conda environment after opening the repository

```bash
conda create -n venv_multiai python=3.10 -y
```
```bash
conda activate venv_multiai
```

## STEP 02- install the requirements

```bash
pip install -r requirements.txt
```

Create a .env file in the root directory and add your GOOGLE_API_KEY credentials

as follows:

```bash
GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

```bash
# Finally run the following command
streamlit run app.py
```
Now,

open up localhost:
Techstack Used:
- Python
- Google API
- Streamlit
- PaLM2
- s2t
- t2s