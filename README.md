# My project's README


# for virtualenv for python 3
sudo apt-get install virtualenv
virtualenv -p python3 venv

# instll pythen dev
sudo apt-get install python3-dev


# For configuring jupyter-notebook on google cloud machine

jupyter-notebook --generate-config

a file will be create ~/.jupyter/jupyter_notebook_config.py
add following at the end of the file

c = get_config()
c.NotebookApp.ip = '*'
c.NotebookApp.open_browser = False
c.NotebookApp.port = 5000

