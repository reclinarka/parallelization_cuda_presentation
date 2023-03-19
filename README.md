# parallelisation_cuda_presentation
Code for a Presentation about Parallelisation and Cuda

----

## Usage
Use Anaconda 3 to create an environment using the ``` environment.yaml ``` file

Navigate into the project folder and use the commands:
```
conda env create -f environment.yaml
conda activate cuda
```
after that you may start jupyter notebook by using the command
```
jupyter notebook
```

----

For using the Web Scraper to gather steam hardware survey, use the command: 
```
wayback-machine-scraper -a 'store.steampowered.com/hwsurvey$' store.steampowered.com/hwsurvey
```
