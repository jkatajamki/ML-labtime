# Task 1 - Tensorflow music generator


## Objective of task
Make sure you can run tensorflowy Machine Learny wibbly wobly stuff without your device catching fire

## What you need

### Repo
clone the forked repo (so we can fiddle with it if we want)

```
git clone https://github.com/NewThingsCo/tensorflow-music-generator
```

### Python
Install python 3 and then some useful packages used in the tasks

``` brew install python3'''
    pip3 install pandas
    pip3 install msgpack-python
    pip3 install numpy
    pip3 install glob2
    pip3 install tqdm
    pip3 install py-midi
``` 

### Tenserflow
We are using the CPU only version which can be installed as per below

```
 pip install tensorflow
 ``` 

### Problems
It seems some things arent working out of box with the pyhton midi player, if you run into errors run the below, then run the `rbm_chords.py` again

```
pip3 install git+https://github.com/vishnubob/python-midi@feature/python3
```

### Output
Output will appear in `/out`

You can play it using something like timidity, or VLC media player

``` 
brew install timidity
``` 
