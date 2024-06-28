
![Invoice_Extractor_App](https://socialify.git.ci/p2kalita/Invoice_Extractor_App/image?language=1&name=1&owner=1&pattern=Signal&stargazers=1&theme=Light)
# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/p2kalita/Invoice_Extractor_App/
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -p venv python=3.10 -y
```

```bash
conda activate venv/
```

### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your GOOGLE API credentials as follows:

```ini
GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```




# Finally run the following command
```
streamlit run app.py
```

Now,

```
open up localhost:
```


![alt text](https://github.com/p2kalita/Invoice_Extractor_App/blob/main/Capture.JPG)



### Techstack Used:

- Python
- LangChain
- Gemini
- Streamlit
- CromaDB


