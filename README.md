# kaggle-tensorflow-speech-recognition-challenge

# for virtualenv for python 3
sudo apt-get install virtualenv <br/>
virtualenv -p python3 venv

# instll pythen dev
sudo apt-get install python3-dev


# For configuring jupyter-notebook on google cloud machine

jupyter-notebook --generate-config

A file will be create ~/.jupyter/jupyter_notebook_config.py
add followings at the end of the file

c = get_config() <br/>
c.NotebookApp.ip = '*' <br/>
c.NotebookApp.open_browser = False <br/>
c.NotebookApp.port = 5000

