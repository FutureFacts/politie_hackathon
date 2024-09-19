# politie_hackathon
Voor de hackathon van de politie. Het verwerken van data voor het identificeren van grootste water vervuilers en voorspellen van missende data in toxische druk.

# Data
Download de dataset zoals beschreven in de mail, en plaats de `datasets` folder hier.

Ik heb de sub-folder `0_Start_Jupyter_notebooks` al verplaatst naar de root directory. 

# Repo Setup
Ik heb zelf de setup gedaan met [uv](https://docs.astral.sh/uv/).

de virtual environment wordt vanzelf gemaakt bij het runnen van 
```
uv run <script name>
```
Voorbeeld script is `hello.py`. Als je dit runt, resolved het als het goed is ook al missende dependencies uit the toml file.  

Voor het toevoegen van dependencies gebruik 
```
uv add <PACKAGE NAME>
```
Als het een development only package is, kan je de `--dev` flag toevoegen. 

Voor het snel runnen van 1 malige packages, zoals bijvoorbeeld ruff of pytest, kan je `uvx` gebruiken: 
```
uvx ruff hello.py
```


