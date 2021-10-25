# Setup Your Build Environment
This is a Guide which will show you how to setup your Build Environment.

## Minimum Requirements

### For the Build System:
- A Linux Evironment (Ubuntu Prefered)
- An 8 thread CPU (You can your even lower spec but it will affect the build Time by a huge margin)
- 16GB RAM
- 300GB of Storage
- A Good Internet Connection (Your internet speed will directly affect your Source syncing time)

### For YOU:

- Basics of Git and Linux.
- Device Trees.
- An Account in a web-based hosting service for Git repositories ie Github or Gitlab.

## Setup Your Environment 

Execute the Following Commands to install the necessary tools (Thanks to AkhilNarang for the Script)

``` bash
mkdir ~/bin

PATH=~/bin:$PATH

cd ~/bin

curl http://commondatastorage.googleapis.com/git-repo-downloads/repo > ~/bin/repo

chmod a+x ~/bin/repo

git clone https://github.com/akhilnarang/scripts.git scripts

cd scripts

bash setup/android_build_env.sh
```
Now setup your git environment using the below command:

```bash
git config --global user.name "Your Name"
git config --global user.email "yourusername@email.com" 
```

Alright your are good to go know.
Sync the ROM and Devices sources and start Building. Good Luck.
