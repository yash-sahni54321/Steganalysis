
## Ultimate Steganography software:

The do all steganography application.:grin:<br>
**Formats Supported-**

- Images
- Audio
- Text
- ~~Video~~ _To be supported in future version_

>This is an important application especially in today's world.<br>
> We need to hide the messages rather than only encrypting them.

## Features

- Hide your private messages in images, audio & text files.
- Forgot password in case you forget. <br>
(Click on the _3 dots_ in main window to know more)
- Access info about any button just by hovering on it.

Using those those _3 dots_ present in topright of the above window, user can create an account in case they forget the password for their repective hidden messages in files.

## Other Notes

All modules are standard modules of **batteries included** python. Then use the `main.py`.
**Having `Cascadia Code` font makes the GUI look best.**
Rest the GUI is quite explanatory so hope you don't have any problem using this.
In audio steganography only `.wav` files are supported presently. In images are formats are supported.



## Installation Instruction

```
# Your global Python installation needs to have pipenv
pip install pipenv

# Clone the repo
git clone https://github.com/aloner-pro/Steno

# Change directories into the project
cd Steno

# [developer only] If you are developer you need to install dependencies for dev
pipenv install --dev

# If you're not a developer just install required dependencies like this
pipenv install

# Activate the Pipenv shell (aka tell your terminal/whatever to use dependencies from the env in this project)
pipenv shell

# Start the program
python -m main.py
```

