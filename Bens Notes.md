for docker builds need to be in the ompl or ompl app folder. -f flag to pass in the docker file to use.
Had ot comment out spot stop, butotherwise the containers built.

# Running ompl app
Get an import error in python
Told VSCode to use GCC and guild it, so that's running now.

Googled; https://github.com/ompl/ompl/issues/1110
apt installed pypy3

Reran build (with gcc) via VSCode
Then with clang
cmake variables are set to generate python bindings.
in build directory ran `ninja update_bindings`