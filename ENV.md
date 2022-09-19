# python
brew install python@3.10  
python3 -m pip install --upgrade setuptools  
python3 -m pip install --upgrade pip  

# virtual env
pip3 install virtualenv  
virtualenv env  

source env/bin/activate  

# install common libs
pip3 install --upgrade jupyter matplotlib numpy pandas scipy scikit-learn  

# run jupyter
jupyter notebook

# fastbook  
pip3 install --upgrade fastbook

# notebook extensions
pip3 install jupyter_contrib_nbextensions
jupyter contrib nbextension install --user


