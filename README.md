# REDigest
REDigest: a Python GUI for *In-Silico* Restriction Digestion Analysis for Gene or Complete Genome Sequences

## Dependencies
REDigest is written in **Python3**, not adapted for python2 and its dependencies.

To use REDigest, following dependencies must be installed, (for python3, version ≥) 

1. tkinter (8.6)
2. Biopython (>=1.78)
3. Pandas (1.1.1)
4. Matplotlib (3.3.1)

## Running REDigest

### With virtualenv (recommended)

In order to keep the REDigest requirements from clogging up the system dirs, it is recommended to install these in a virtual environment. This is also recommended in order to keep required packages at their proper versions.

```
# make the virtual environment
python3 -m venv venv

# activate it (Linux/Mac)
source venv/bin/activate

# (or) activate it (Windows)
venv\bin\activate.bat

# install required packages

## update the environment
pip install -U pip
pip install -U setuptools wheel


# download the repository
git clone https://github.com/abhijeetsingh1704/REDigest
cd REDigest

## install dependencies
pip install -r requirements.txt
```

After setting up the virtual environment, it simply needs to be activated before running the software. After activating, the software is executed by running
```
python REDigestGUI.py
```


# GUI tab for restriction digestion analysis

### input file = fasta or genbank file

![alt text](https://github.com/abhijeetsingh1704/REDigest/blob/master/REDigest.png?raw=true)



#


# GUI tab for visualization

### input file = .csv file generated by restriction digestion from tab 1

![alt text](https://github.com/abhijeetsingh1704/REDigest/blob/master/REDigest2.png?raw=true)


#


### Without virtualenv

#### On windows
* Add execution permission if necessary to script `REDigestGUI.py`

    *In the order of priority*
1. Double click to open the REDigest GUI
2. In command prompt type and execute `python3 REDigestGUI.py`

#### On Linux/MacOS
* In terminal, add execution permission if necessary with `sudo chmod +x REDigestGUI.py`

    *In the order of priority*
1. In terminal type and execute `python3 REDigestGUI.py`
2. In file explorer, right click on file and execute **Run in terminal**
3. Double click to run REDigest GUI **NOTE:** *this option might not work on some linux distro, depending on the system permissions*

# Citation
REDigest: a Python GUI for In-Silico Restriction Digestion Analysis of Genes or Complete Genome Sequences.
Abhijeet Singh
bioRxiv 2021.11.09.467873; doi: https://doi.org/10.1101/2021.11.09.467873
