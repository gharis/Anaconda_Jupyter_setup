# Anaconda Jupyter setup
Install anaconda from https://www.anaconda.com/products/individual
## Anaconda prompt run as administrator 

Use following commands 

    pip install numpy
 
    conda update --all

    pip install tensorflow

## if get error --> 

    ERROR: Cannot uninstall 'wrapt'. It is a distutils installed project and thus we cannot accurately determine which files belong to it which would lead to only a partial     uninstall.
    https://github.com/tensorflow/tensorflow/issues/30191

use command --> 
    pip install wrapt --upgrade --ignore-installed

    pip install tensorflow

## Go to file derectory to run jupyter note book

Anaconda prompt 

    (base) C:\WINDOWS\system32>cd /
 
    (base) C:\>cd

    (base) C:\>cd Users/

    (base) C:\Users\GamitH>cd Downloads

    (base) C:\Users\GamitH\Downloads>jupyter notebook

    (base) C:\Users\GamitH\Downloads>jupyter notebook

    [I 22:14:03.541 NotebookApp] JupyterLab extension loaded from C:\anaconda\lib\site-packages\jupyterlab

    [I 22:14:03.541 NotebookApp] JupyterLab application directory is C:\anaconda\share\jupyter\lab

    [I 22:14:03.821 NotebookApp] Serving notebooks from local directory: C:\Users\GamitH\Downloads

    [I 22:14:03.821 NotebookApp] 0 active kernels

    [I 22:14:03.821 NotebookApp] The Jupyter Notebook is running at:

    [I 22:14:03.822 NotebookApp] http://localhost:8888/?token=92c014228e6cd009574c28f9fa10557c32f2e03de0421c54

    [I 22:14:03.822 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
    [C 22:14:03.824 NotebookApp]
    
    Copy/paste this URL into your browser when you connect for the first time,
    to login with a token:
        http://localhost:8888/?token=92c014228e6cd009574c28f9fa10557c32f2e03de0421c54

    [I 22:14:04.376 NotebookApp] Accepting one-time-token-authenticated connection from ::1



