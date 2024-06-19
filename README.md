# FOOOCUS-MRE-ANDROID-TERMUX-
Fooocus-MRE on android heck yeahhh!!

Fooocus-MRE and Fooocus requires 16 gb ram to run! my laptop has 16gb ram and it can run Fooocus-MRE but it's super SLOW!!
SO basically if u even want to use focus u need 18gb ram but 16gb is minimum!



pkg updated && pkg upgrade -y && termux-setup-storage &&
pkg install wget -y && pkg install git -y && pkg install proot -y &&
cd ~ && git clone https://github.com/MFDGaming/ubuntu-in-termux.git && cd ubuntu-in-termux && chmod +x ubuntu.sh && ./ubuntu.sh -y && ./startubuntu.sh 

2. Installing Fooocus MRE
Run below commands sequentially as root user in Ubuntu

Install basic tools

apt update && apt upgrade -y && apt-get install curl git gcc make build-essential python3 python3-dev python3-distutils python3-pip python3-venv python-is-python3 -y 

Install required extensions

apt-get install libgl1 libglib2.0-0 libsm6 libxrender1 libxext6 -y

Clone the repository

git clone https://github.com/MoonRide303/Fooocus-MRE.git

cd Fooocus-MRE

pip install pygit2==1.12.2

pip install packaging

Fix' the issue with Python running in PRoot

export ANDROID_DATA=anything 

python entry_with_update.py --cpu --force-fp16 --disable-xformers --use-quad-cross-attention

Launch the webui. It will take some time to complete first-time installation then everything should be fine




Navigate to the webui in your browser
http://127.0.0.1:7860 









