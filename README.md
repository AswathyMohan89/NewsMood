# NewsMood

The NewsMood is a python script  that does sentimental analysis on tweets by BBC,CNN,CBS,Foxnews, the New york Times


# instructions
Download Python and conda from the links given below
### Python

mac : Goto https://www.python.org/downloads/ and download latest version

windows : Goto https://www.python.org/downloads/windows/ and download latest version

### conda
mac : Goto https://conda.io/docs/user-guide/install/macos.html follow directions

windows : Goto https://conda.io/docs/user-guide/install/windows.html follow directions

#### Remember to add to PATH variable during installiation
To verify goto (Terminal/GitBash) and type `conda -V` or `conda list`.

#### Create conda environment

`conda create -n PythonData python=3.6 anaconda` 

`source activate PythonData`

`python --version`

### Fork the repo and clone to remote

### Api
Create api keys from  https://apps.twitter.com - Twitter

### Do the following in git(windows)/terminal(mac)

`source activate PythonData`

`pip install tweepy`

#### vader- sentiment analysis

`source activate PythonData`

`pip install vaderSentiment==2.5`

if it doesn't work try creating a new conda env:

`conda create -n newPythonData python=3.6 anaconda` 

`source activate PythonData`

`pip install vaderSentiment==2.5`
`jupyter notebook`

open NewsMood.ipynb in jupyter notebook and enter the twitter credentials. 
Run the code 




