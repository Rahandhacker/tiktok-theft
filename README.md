# tiktok-theft


Testing the available mirrors:
[*] https://dl.bintray.com/termux/termux-packages-24: bad
[*] https://grimler.se/termux-packages-24: ok
[*] https://main.termux-mirror.ml: ok
[*] https://termux.mentality.rip/termux-packages-24: ok
Picking mirror: https://termux.mentality.rip/termux-packages-24
Get:1 https://termux.mentality.rip/termux-packages-24 stable InRelease [14.0 kB]
Ign:2 https://dl.bintray.com/grimler/game-packages-24 games InRelease
Ign:3 https://dl.bintray.com/grimler/science-packages-24 science InRelease
Get:4 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 Packages [414 kB]
Err:5 https://dl.bintray.com/grimler/game-packages-24 games Release
  502  Bad Gateway
Err:6 https://dl.bintray.com/grimler/science-packages-24 science Release
  502  Bad Gateway
Reading package lists... Done
E: The repository 'https://dl.bintray.com/grimler/game-packages-24 games Release' does not have a Release file.
N: Metadata integrity can't be verified, repository is disabled now.
N: Possible cause: repository is under maintenance or down (wrong sources.list URL?).
E: The repository 'https://dl.bintray.com/grimler/science-packages-24 science Release' does not have a Release file.
N: Metadata integrity can't be verified, repository is disabled now.
N: Possible cause: repository is under maintenance or down (wrong sources.list URL?).
$ pkg upgrade -y
Checking availability of current mirror: ok
Hit:1 https://termux.mentality.rip/termux-packages-24 stable InRelease
Ign:2 https://dl.bintray.com/grimler/game-packages-24 games InRelease
Ign:3 https://dl.bintray.com/grimler/science-packages-24 science InRelease
Err:4 https://dl.bintray.com/grimler/game-packages-24 games Release
  502  Bad Gateway
Err:5 https://dl.bintray.com/grimler/science-packages-24 science Release
  502  Bad Gateway
Reading package lists... Done
E: The repository 'https://dl.bintray.com/grimler/game-packages-24 games Release' does not have a Release file.
N: Metadata integrity can't be verified, repository is disabled now.
N: Possible cause: repository is under maintenance or down (wrong sources.list URL?).
E: The repository 'https://dl.bintray.com/grimler/science-packages-24 science Release' does not have a Release file.
N: Metadata integrity can't be verified, repository is disabled now.
N: Possible cause: repository is under maintenance or down (wrong sources.list URL?).
$ pkg install git
Checking availability of current mirror: ok
Reading package lists... Done
Building dependency tree... Done
The following additional packages will be installed:
  pcre2
The following NEW packages will be installed:
  git pcre2
0 upgraded, 2 newly installed, 0 to remove and 49 not upgraded.
Need to get 4030 kB of archives.
After this operation, 19.2 MB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 pcre2 aarch64 10.40 [840 kB]
Get:2 https://termux.mentality.rip/termux-packages-24 stable/main aarch64 git aarch64 2.35.3 [3189 kB]
Fetched 4030 kB in 2s (1982 kB/s)
Selecting previously unselected package pcre2.
(Reading database ... 3457 files and directories currently installed.)
Preparing to unpack .../pcre2_10.40_aarch64.deb ...
Unpacking pcre2 (10.40) ...
Selecting previously unselected package git.
Preparing to unpack .../git_2.35.3_aarch64.deb ...
Unpacking git (2.35.3) ...
Setting up pcre2 (10.40) ...
Setting up git (2.35.3) ...
$ git clone https://github.com/OnlineHacKing/PUBG-Phishing.git
Cloning into 'PUBG-Phishing'...
Username for 'https://github.com': Rahandhacker
Password for 'https://Rahandhacker@github.com':
remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
fatal: Authentication failed for 'https://github.com/OnlineHacKing/PUBG-Phishing.git/'
$ cd PUBG-Phishing
bash: cd: PUBG-Phishing: No such file or directory
$ ls
$ chmod +x *
chmod: cannot access '*': No such file or directory
$ ./Android-Setup
bash: ./Android-Setup: No such file or directory
$
