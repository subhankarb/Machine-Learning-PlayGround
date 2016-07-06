# Machine-Learning-PlayGround
virtualenv ml-playground-env
source ml-playground-env/bin/activate
sh ./install.sh
ipcluster nbextension enable
jupyter notebook --port 9999