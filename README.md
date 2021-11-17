# ani-cli-win
A tool to scrape anime from goganime using WSL and MVP tools in Windows. Tested working on Win10


## Instalation
-Install [wsl] (https://docs.microsoft.com/en-us/windows/wsl/install) in windows
- Install [mpv](https://mpv.io/installation/) in Windows
- go into your wsl and type:
	-  git clone https://github.com/game1men/ani-cli-wsl
	-  cd ani-cli-wsl/
	-  chmod +x ani-cli-wsl 
- now you can run it with ./ani-cli-wsl

## Usage

	# watch anime
	ani-cli <query>

	# download anime
	ani-cli -d <query>

	# resume watching anime
	ani-cli -H

Multiple episodes can be viewed/downloaded by giving the episode range like so

	Choose episode [1-13]: 1 6

This would open/download episodes 1 2 3 4 5 6

## Dependencies

* grep
* curl
* sed
* mpv (in Windows)
