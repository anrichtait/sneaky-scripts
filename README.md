# Synopsis:
A collection of scripts that will make your world spin around a bit faster.
Feel free to submit your ideas in the form of an issue and I will add it to the roadmap here in the readme.

Join me on discord: https://discord.gg/HdsMTrUGau

# What's next/Roadmap?
* Mega Grep Grabs - prompts user for files to search for and copy to a location on the system.
* Battery percent notifier
* Youtube to mp3 (Done but having issues with youtube-dl)
* Document scanner and copier

# Current development stages:

## In development:
* Youtube to mp3 (having issues with youtube-dl)

## On hold:
* Adding a html web scraper to readmeGeny to automagically grab all relevant 
information from the alx projects page.

# Scripts and their descriptions:

## readmeGeny:
Make your ALX projects more professional with a formatted README.md. This script 
generates a README.md after asking the user for the number of questions. It gets
it's basic format from the template.md file.

## trashcan:
This script takes over the rm command to make deleting files safer, too many times
have i deleted huge files or folders due to reckless rm -rfs. **NO LONGER I say!**
Make sure that you add the following line to your .bashrc and also change the script paths
to wherever you save the script.
**alias tc="/path/to/trashcan.sh"**

## cloneWars:
This script makes git cloning a bit easier, it will prompt the user for whether the repo
they are trying to clone is public or personal. If personal it will enter their username and 
token when cloning. If public it will just clone the repo. I still plan on creating 
a script that will cache your token so you don't  have to enter it, but for now I am happy
with this. **Please remember to change the script variables gitUserName and gitToken to your own
or personal cloning will not work!**

## youtubeMP3:
This script is a youtube to mp3 converter/downloader. It is not currently working
due to a youtube-dl(program) error that I am struggling to resolve, this will be fixed in the future.
