# ARISE model (UK version)

**Concept:**
Dr. Gino Baudry (EPFL, Imperial College London, gino.baudry[at]epfl.ch)

## Setup

### Software

1. Install 
<a href="https://www.anaconda.com/" target="_blank">Anaconda 3</a> (last available version)

2. Install 
<a href="https://www.knime.com/downloads" target="_blank">KNIME Analytics platform</a> (version 4.5.2)

3. Install 
<a href="https://powerbi.microsoft.com/en-gb/downloads/" target="_blank">Microsoft Power BI</a> (free version)

### Virtual environment

Create a Python virtual environment using Anaconda 3:

Save the following text as "__py36_knime452.yml__" in Anaconda 3: 

```
name: py36_knime452
channels:
- defaults
- anaconda
dependencies:
- python=3.6      
- pandas=0.23         
```
In Anaconda prompt, create the virtual environment: 

```
conda env create -f py36_knime452
```

Activate and update any packages if necessary.

```
conda activate py36_knime452
```
### KNIME workspace
Run KNIME as an administrator and choose a Workspace. This can be setup at your convenience.
### Python environment
This can be set in the KNIME preferences by browsing to the Python.exe that is inside your virtual working environment.

## ARISE
Open the ARISE workflow and use the attached documentation for Help.
### Pathway computation
Explore the multiple levers at your convenience and hit the "execute all" button. 
You can name your Pathway and activate the saving option to export it in the pathway explorer.

### Pathway explorer
Run Power BI and open ARISE data to explore the pre-saved pathways as well as yours.
