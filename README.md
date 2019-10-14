# scripts
A collection of Bash scripts.

## Make the script executable
```bash
$ chmod u+x nameOfScript
```

## Make the scripts available global
```bash
$ mkdir -p ~/scripts
$ export PATH="$PATH:~/scripts"
```

Next edit your .bash_profile file to include export PATH="$PATH:~/scripts" that will keep the "scripts" folder in your path every time you log in.

With the script saved in the folder, you can now run it with just:
```bash
$ nameOfScript
```
