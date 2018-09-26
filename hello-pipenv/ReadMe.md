## pipenv
create the dir you work in...
go to that dir
pipenv --python path to python - for me just python - it's just py3
i can just do... pipenv --python python

pipfile - packages that you installed directly
pipfile.lock - all the dependencies and version numbers

that create virt env for that version of python
pipenv shell - this opens a shell for that env

exit() -- exits from python

usefull command pip freeze
pip freeze -- will show everything in the venv
python -version
in the command pallete...
can also type python: select interpreter DON'T NEED THIS...it create the file.

Key commands

exit => this will exit the shell.. just exit NOT pipenv exit
pipenv install => this installs everything from the pipfile. this will also add the pipfile.lock
pipenv --where => tells your current working directory
pipenv install -r requirements.txt
pipenv update => will update packages, or specific versions
pipenv update requests => or can add specific version


----------------------------
the pipfile can be passed around.... then just do
pipenv install -- this installs everything from the pipfile. this will also add the pipfile.lock

exit => this will exit the shell.. just exit NOT pipenv exit

pipenv --where => tells your current working directory
if you moved to parent directory it would tell you not in env.
can install a specific package with...
like..
pipenv install django

to install from requirements.txt
pipenv install -r requirements.txt

pipenv update => will update packages, or specific versions

pipenv update requests => or can add specific version

