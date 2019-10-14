# scripts
A collection of Bash scripts.

## Make the script executable

$ chmod u+x sugh.sh

## Make the scripts available global

$ mkdir -p ~/scripts
$ export PATH="$PATH:~/scripts"

Next edit your .bash_profile file to include export PATH="$PATH:~/scripts" that will keep the "scripts" folder in your path every time you log in.

With the script saved in the folder, you can now run it with just:
$ nameOfScript
