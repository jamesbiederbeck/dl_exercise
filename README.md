# Deep Learning Exercise
Here you'll find a data science exercise that may be solved with deep learning techniques.  While you're encouraged to use deep learning, this problem can certainly be solved other ways.  Be sure to document your thought processes and justify *why* you used your solution.

## Limits
You shouldn't spend longer than 1-2 hours on this challenge.  You won't be timed so be sure to relax and choose a time that suits you.  It's perfectly acceptable if you don't complete the exercise.  Just be sure to document your progress and explain your strategies.  You're encouraged to use and cite prior research.

## The Problem
The goal of this exercise is to build a reliable heartbeat detector given electrocardiogram (ECG) data.

## The Data
For this exercise we'll be using ECG data from the [MIT-BIH Arrhythmia Database](https://www.physionet.org/physiobank/database/mitdb/).  There's a handy tool [here](https://physionet.org/cgi-bin/atm/ATM) for converting this data to more usable formats.  The first data file, `100m.mat`, is already in the same directory as this notebook so you won't need to download anything unless you wish to collect more data.  If you do, use the [ATM](https://physionet.org/cgi-bin/atm/ATM) to export `.mat` files.  The annotations are obtained by selecting `Show annotations as text`.  Be sure to move the `Aux` column if you import more annotations.

## Getting Started
This exercise is contained within a [Jupyter Notebook](http://jupyter.org).  Once you have Jupyter installed, simply open the notebook by running:

     jupyter-notebook deep_learning_exercise.ipynb

Then point your browser [to the local notebook server](http://localhost:8888/notebooks/deep_learning_exercise.ipynb).
