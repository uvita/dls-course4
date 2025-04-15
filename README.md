# dls-course4
Deep Learning Specialization - Course 4 - Convolutional Neural Networks

To run locally (using VS Code), **install pyenv + virtualenv**

`brew install pyenv pyenv-virtualenv`

Install Python version, e.g.

`pyenv install 3.7.17`

cd into the working directory and **create a virtual env** with desired Python version:

`pyenv virtualenv 3.7.17 dls-c4`

Activate the virtual env:

`pyenv local dls-c4`

Install needed Python libraries

`pip install -r W1A1/requirements.txt`

`pip install nbconvert` #to avoid syncing cell's output - See https://gist.github.com/33eyes/431e3d432f73371509d176d0dfb95b6e

`pip install tensorflow==2.3.0`

`pip install Pillow`

`pip install pandas`

For W2A1 Python 3.8.10 is required as well as Tensorflow 2.9.1
`pyenv virtualenv-delete dls-c4`
`pyenv install 3.8.10`
`pyenv virtualenv 3.8.10 dls-c4-w2`
`pyenv local dls-c4-w2`
`pip install nbconvert`
`pip install tensorflow==2.9.1`
`pip install numpy==1.22.3`
`pip install scipy==1.7.3`
`pip install matplotlib`