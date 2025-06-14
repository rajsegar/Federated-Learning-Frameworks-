# Federated-Learning-Frameworks-
FL Frameworks installation in AWS Environment 

# pip Installation

# Python 3 – pip Installation on Ubunthu

Enable the Universe Repository = sudo add-apt-repository universe

Update Your Package Lists = sudo apt update

Install python3-pip = sudo apt install python3-pip

Confirm Installation = pip3 –version

Use a Virtual Environment Safe + Best Practice

Make sure venv is installed = sudo apt install python3-venv python3-full -y

Create a virtual environment = python3 -m venv flwr-env

Activate the virtual environment = source flwr-env/bin/activate

Now install Flower and other dependencies = pip install --upgrade pip

pip install flwr torch torchvision opacus

python -c "import flwr; print('Flower installed successfully')"
