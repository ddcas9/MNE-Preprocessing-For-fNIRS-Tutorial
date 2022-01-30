# MNE-Preprocessing-For-fNIRS-Tutorial

This tutorial notebook comes from the MNE docs as well as my own notes on a webinar on MNE with fNIRS data presented at NIRx that is freely available on youtube.

## Running Locally

To run this notebook locally, set up a virtual environment with venv (here I create one named 'venv' after the venv command, but you can name it anything):

```
python3 -m venv venv
```

Then activate your virtual environment:

```
source ./venv/bin/activate
```

And install the requirements.txt file using pip3:

```
pip3 install -r requirements.txt
```

Then run jupyter with `jupyter notebook`. Note that you can use the installed modules from requirements in this jupyter notebook only because you install jupyter in the virtual environment. If you have jupyter installed on your system, and it wasn't included in requirements.txt, you wouldn't be able to import the relevant modules unless you install them system wide. 
