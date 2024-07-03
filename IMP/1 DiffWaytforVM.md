# Different ways to create vertual env to work for us
1. just if we have python with us then

python -m venv my_env
    my_env is the folder which will be created 

activate it (the folder will have scripts and activate file in it)
my_env\Scripts\activate
    so this activates it 

then here we can pip install any packages
the python version installed in this is of our system ka only
if multiple libraries then we can create requirements.txt and then we can do 
pip install -r requirements.txt
this will install all the libraries mentioned in requirements.txt file

to deactivate it 
deactivate command is written


2. for Linux and all

pip install virtualenv

virtualenv -p python3 virtual_env
virtual_env is the folder
then to activate we do
virtual_env\Scripts\activate
it activates it again
then to deactivate we run
deactivate

then can install packages

3. using conda
shd have anaconda installed in ours
conda create -p my_env python==3.10 -y
allows to create with name as my_env and also if diff python in ours also we can create here then we can do this and then install diff things

to activate we can do conda activate my_env/ it activates it then can use it in others


if ipynb we have then we can select diff kernels and our env and for ipynb main thing req is the 
# ipykernel is req so first pip install this in our env then in ours we can then run the ipynb files 
main folder inside that a venv folder we do and in main folder only the ipynb files and all and just run using the env for us