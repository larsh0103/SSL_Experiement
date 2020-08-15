This project uses piptools to manage the virtual environment.

Therefore follow the following setup procedure.


1. Create Virtual enviroment
python -m venv .venv --prompt="ssl_experiment"
2. Initiate virtual environment
```
source .venv/bin/activate
```
3. Install pip-tools
```
pip install pip-tools
```
4. Install all required packages from requirements.txt
```
pip-sync
``` 
5. Start jupyter notebook server and open the ssl notebook
```
jupyter notebook
```