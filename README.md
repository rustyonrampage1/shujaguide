# shujaguide

# Step 1: Start the Python 2 environment in VSCODE
### Download VS Code
Open the project in VS code

### Setup anaconda 2 environment
https://docs.anaconda.com/anaconda/user-guide/tasks/switch-environment/

### Run the commands in VS code terminal (cntrl+J)
conda create --name py2 python=2.7
activate py2

# Step 2: Ensuring all the required packages are installed in this new py2 environment
1. Search windows and open Anaconda Navigator
2. Go to Environments Tab
3. Click py2
4. Select All Pacakges dropdown
5. Find nltk package and install it
6. Also install anyother package that is mentionned in the project
7. If some package is not available in the conda packages repo, then you'll have to install it by searching on Google and using command line (use the VSCode one as you have already activated py2 to be used there for time being)

# Step 3: Install NLTK Corpus
1. In VScode command line, start python code by typing just 
python # it starts the python inline code executor
import nltk
nltk.download()
2. A mini application will open in the windows taskbar, Click on it and download everything

# Try running the code
In vscode cmd, write python sentiment.py

