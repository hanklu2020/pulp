


1. create a new github repository ex. jupyter_notebook_and_tensorflow
2. create a empty python file ex. main.py
3. clone the github repository to repl.it ("import repo")

tensorflow-cpu:
a. pip install --upgrade pip
b. pip install --upgrade tensorflow-cpu
c. python3 -c 'import tensorflow as tf; print(tf.__version__)'

jupyter_notebook:
1. type these in terminal(in order):
a. pip install --upgrade pip
b. pip install notebook
c. (jupyter --version ← if you want to check)
d. jupyter notebook --generate-config
e. jupyter notebook password # Enter and confirm the password
f. jupyter notebook --ip=0.0.0.0 --port=3000


if you want to save them back to github:
1. git init
2. git add .
3. (git status ← if you want to check)
4. git commit -m "<anything>"
5. git push -u origin master

Run:
1. @.replit file, replace ' run = "" ' with ' run = "jupyter notebook --ip=0.0.0.0 --port=3000" '
2. click the "Run" button and here you go

_______________________________________
os.system('pip uninstall PySimpleGUIWeb')

import tensorflow
1. pip3 install --upgrade tensorflow
2. python3 -c "import tensorflow as tf; print(tf.reduce_sum(tf.random.normal([1000, 1000])))"

