# ML-for-InfoSec

In order to train and test your models you need to have an environment with deep learning libraries. THose instructions will get your environment all at once. 
PLEASE NOTE. THose instructions are good only for 

Mac OSX Sierra 10.12.4
Ubuntu 16.04
Windows 10

If you have previous versions of OS go ahaead and upgrade and then follow those instructions.


Clone this repository on your local computer

git clone https://github.com/angelsonly/ML-for-InfoSec.git

Download and Install Anaconda Python 3.6 from their official webpage

https://www.continuum.io/downloads

Change to course folder

cd ML-for-InfoSec

Create the course environment

conda env create

wait for the environment to create.

Activate the environment (Mac/Linux)

source activate ML-for-InfoSec

Activate the environment (Windows)

activate ML-for-InfoSec

Check that your prompt changed to

ML-for-InfoSec $

Launch Jupyter Notebook 

jupyter notebook

Open your browser to

http://localhost:8888


Run the Check environment Notebook

Go to the course folder, open the notebook Check_Environment.ipynb and run it. If you see the message:

Houston we are go!


You are all set!


To remove the environment:

close the browser and go back to your terminal

stop jupyter notebook (CTRL-C)

deactivate the environment (Mac/Linux):


source deactivate


deactivate the environment (Windows 10):


deactivate ML-for-InfoSec



Troubleshooting. Simplest way - to remove everything and install once again by typing




$ conda remove -y -n ML-for-InforSec --all

$ conda clean --all



