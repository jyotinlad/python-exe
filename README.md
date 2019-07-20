# Python Executable

## Overview
A A mechanism to convert Python scripts in executables. to convert Python scripts in executables.
 
## Prerequisites
The python packages `pyinstaller` and `pywin32` must be installed (as follows when using Anaconda).
```
conda install -c conda-forge pyinstaller
conda install -c anaconda pywin32
```

## Instructions
The executable can be created by running the following command:

`C:\ProgramData\Anaconda3\Scripts\pyinstaller --onefile <file_name>.py`

This will create the file in the `dist` directory, wherever the command is run from.
