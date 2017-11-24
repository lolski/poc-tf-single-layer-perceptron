eval "$(pyenv init -)"
pyenv local 3.6.1
virtualenv -p python3 .
source bin/activate
pip3 install --upgrade https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-1.3.0-py3-none-any.whl # somehow pip3 install tensorflow doesnt work
