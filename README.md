#### Python Obfuscator method ###### For continous obfuscation check please install:

pip install pre-commit

please review the logic in .pre-commit-config.yaml

after you have to install before you can use:

pre-commit install

It will auto-triggered during comits.

You can check your files any time:

pre-commit run --files <filename>

pre-commit run --all-files


#### Python auto import - generating requirements.txt content and pip auto installs it ######

Simply run:
setup_env.py

it will output any further actions
