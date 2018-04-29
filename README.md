# Find-Vulnerable-Methods
Using python code to find vulnerable methods in C

After you git clone the repo, install pycparser so we can iterate through the C code methods in a simpler way

pip install pycparser

python findExploits.py C-File MethodName

Example: python findExploits.py hash.c malloc
