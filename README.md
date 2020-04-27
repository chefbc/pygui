# pygui

# https://medium.com/better-programming/my-simple-python-development-setup-687c31898d5b

# Install via homebrew
brew install pyenv

# Update profile
echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bash_profile
echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bash_profile
echo -e 'if command -v pyenv 1>/dev/null 2>&1; then\n  eval "$(pyenv init -)"\nfi' >> ~/.bash_profile

# Show the list of available python versions
# If you don’t see the python version you may try updating pyenv to its latest version
pyenv install --list
# Install the version you want
pyenv install -v 3.7.5
pyenv install -v 3.8.0


python -V


pyenv shell 2.7.17


pyenv shell 3.8.0
# List your installed python versions (The * will indicate your current version)
pyenv versions
# Change your global python version
pyenv global 3.7.5
# Sets a location specific python version (creates a .python-version file)
pyenv local 3.7.5
# Uninstall any version
pyenv uninstall 3.7.5



# Create virtual environment python2
pyenv versions
pyenv shell 2.7.17
python -V
pip install virtualenv
virtualenv env
source env/bin/activate




# Create our virtual environment named “env”
python -m venv pygui


# /bin/python3.6 -mvenv /opt/ads36-venv/
# A python installation in a new env folder will be created.
# Activate your virtual env
source pygui/bin/activate
# You’ll be working in your virtual environment…. Happy hacking!
# To leave your virtual environment
deactivate


pip install -r requirement.txt


python -m venv env
source env/bin/activate


PYTHON_CONFIGURE_OPTS=

https://github.com/jiansoung/issues-list/issues/15
https://github.com/pyenv/pyenv/issues/1375
PYTHON_CONFIGURE_OPTS="--with-tcltk-includes='-I/usr/local/opt/tcl-tk/include' --with-tcltk-libs='-L/usr/local/opt/tcl-tk/lib -ltcl8.6 -ltk8.6'" pyenv install 3.7.4

PYTHON_CONFIGURE_OPTS="--with-tcltk-includes='-I/usr/local/opt/tcl-tk/include' --with-tcltk-libs='-L/usr/local/opt/tcl-tk/lib -ltcl8.6 -ltk8.6'" pyenv install 3.7.4

source pygui/bin/activate
pip install -r requirement.txt


https://dev.to/codemouse92/dead-simple-python-project-structure-and-imports-38c6



https://github.com/mousepawmedia/omission

https://dev.to/codemouse92/dead-simple-python-project-structure-and-imports-38c6

https://medium.com/free-code-camp/how-to-set-up-continuous-deployment-in-your-home-project-the-easy-way-41b84a467eed





https://stackoverflow.com/questions/1470572/ignoring-any-bin-directory-on-a-git-project

git rm -r --cached bin

cat .gitignore
/pygui/*