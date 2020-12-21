# linux-config

My linux machine configuration files.

### Installation

Install the necessary packages:

```
sudo apt install i3 i3blocks i3-agenda
```

Copy the configuration files:

```
git clone https://github.com/yedhukrishnan/linux-config.git
cd linux-config
cp -r i3 ~/.config
cp .Xmodmap ~/.Xmodmap
```

### Points to Note

1. Expects the Google credentials at `~/.google_credentials.json`. (Refer the [i3-agenda](https://github.com/rosenpin/i3-agenda) repo for instructions)
