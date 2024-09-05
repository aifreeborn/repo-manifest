# repo-manifest
Source Manifest

Install the `repo` utility:
---------------------------

To use this manifest repo, the `repo` tool must be installed first.

```
$: mkdir ~/bin
$: curl http://commondatastorage.googleapis.com/git-repo-downloads/repo  > ~/bin/repo
$: chmod a+x ~/bin/repo
$: PATH=${PATH}:~/bin
```

Download the Yocto Project BSP
------------------------------

```
$: mkdir <release>
$: cd <release>
$: repo init -u https://github.com/aifreeborn/repo-manifest -b <branch name> [ -m <release manifest>]
$: repo sync
```
