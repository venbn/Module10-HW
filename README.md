
## Dev

I use Jupyter notebook to write the Python code, this code is built in Jupyter notebook on a Mac PC. 
The process must be pretty much same when executing from GitBash on WindowsPC except that you will need Visual Studio Code to install required extensions/moduled.
To ensure, a suitable environment is existing to execute this code, you will need to have python3 and pip3 installed already. 
Python versions older than 3 might not function effeciently. The Python version used to write this code is 3.10.6, any verison of Python3 should work.

## Dependencies

Apart from python3 and pip3, you will need to have jupyter, anaconda and matplotlib installed at the operating system level.
All the dependent librariries required to successfully use pandas and sklearn modules must be installed, the code is heavily dependent on pandas, hvplot,pathlib and sklearn modules.

Following modules must be already installed before running the code and conda environment must be activated as well. To execute the code, Jupyter notebook must be used. 

Below commands are Mac compatible.

pip3 install conda
pip3 install anaconda3
conda install hvplot
pip3 install scikit-learn

Before running the code, conda environment must be created and activated.

conda create -n cenv python=3.10.6
conda activate cenv

## Pre-requisites

Ensure all the below csv files are existing on the OS from where you are executing the code. You will need to run "Jupyter notebook" from the same directory (Module10-HW) where all the files exist. Below is the list of files which need to exist for the successful execution of the code.

crypto_market_data.csv
crypto_investments.ipynb
README.md

Git must be installed. If using Windows GitBash must be installed.

To execute the code from Windows - you will need Visual Studio Code installed as well to look at the code.

The file 'crypto_investments.ipynb' is the file to be opened from the 'Jupyter notebook' interface ONLY.

## Execution process

Clone the directory which contains all the .csv files and the .ipynb file to your system using the following commands

git clone https://github.com/venbn/Module10-HW.git

Once the clone completes.. 

Go to the directory "Module10-HW"

cd Module10-HW

Execute 'Jupyter notebook' command

In the Jupyter notebook interface, open the file 'crypto_investments.ipynb'

You should be able to see the code
