# Installation
You need Python3.6 to run the scripts.
Install requirements listed in `requirements.txt`

# Usage
## Inference mode 
Run `python3 test_parse.py <file_name> -l <N>` , where `<N>` is the number of chars, e.g. 1000. This parameter is optional, but processing the whole file may take too much time.

## Importing text
Run `python3 import_text.py <file_name> -l <N>`, `<N>` is the number of chars, e.g. 1000. 
The script willl generate `freq_editor` file in the `editor` folder.

## Updating knowledge base
After updating files in the editor folder run `python3 update_kb.py`. 
The script will update knowledge base and generate new editor files.
# EDA
