# GitHub Build Status

<img width="318" alt="screen shot 2018-08-17 at 2 16 18 pm" src="https://user-images.githubusercontent.com/1690993/44282196-4718cf80-a228-11e8-9295-186daa582c48.png">


Display GitHub CI build status in Sublime Text. 

The badge: `Build x+y-z?` where `x` is the number of successful builds, `y` is the number of failures + errors (if any) and `z` is the number of pendings.


## Installation

GitHubBuildStatus is available to be installed via Package Control.


To install manually, clone the package manually to your Package directory. It would be eventually published to Package Control once it gets more mature.

```sh
# on macOS
cd "$HOME/Library/Application Support/Sublime Text 3/Packages"
# on Linux
cd $HOME/.config/sublime-text-3/Packages
# on Windows (PowerShell)
cd "$env:appdata\Sublime Text 3\Packages\"

git clone git@github.com/randy3k/GitHubBuildStatus.git
```

## Show Build Status Details

Run `Github Build Status: Details`

<img width="800" src="https://user-images.githubusercontent.com/1690993/44185676-eaf86300-a0e2-11e8-9273-348313729e87.png">


## Settings

You are also recommended to provide your own [github api token](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/) to allow more frequent refreshes and access to your private repos. Simply run `Preference: GitHub Build Status` and edit the `token` setting.