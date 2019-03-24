# python_setup_py
Setup.py example.

This project is example of using `multiply` as module using setup.py and easy_install.

Steps:
--------------------------------------------------------Installing------------------------------------------------------------
1. Clonning project: git@github.com:DmitrSh/python_setup_py.git
2. Create virtualenv: python3.6 -m venv venv
3. Activate virtualenv: source ./venv/bin/activate
4. Create .egg package: python setup.py bdist_egg --exclude-source-files
5. easy_install ./dist/multiply-1.0-py3.6.egg


--------------------------------------------------------Using-----------------------------------------------------------------
In your python module include multiply: 
from multi.multi import multiply
multiply(2,1)
