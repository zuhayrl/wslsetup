# WSL Setup
A quick simple guide to download setup WSL (Windows Subsystem for Linux)

## Pre-Installation
Before installing WSL go to the search bar in the start menu and type: "turn windows features on or off". Click on the corresponding "app" and then find Windows Subsystem for Linux. Check the Box.
Now you're ready to install WSL.

## Installation
The easiest way to install WSL is through the command prompt/terminal. The command prompt can be opened by pressing Windows Key + R. A small window will open and there will be a textbox next to the words "Open". Type "cmd" in the textbox and press enter.
Alternatively, you can open the command prompt by searching for it in the start menu.

Once you have the terminal open you want to enter the following:

```sh
wsl --install
```

It should look like this:

<img width="600" alt="Installation Screen" src="https://i0.wp.com/pureinfotech.com/wp-content/uploads/2020/11/install-wsl-windows-11-command.jpg?w=1011&quality=78&strip=all&ssl=1">

You will then need to restart your computer.

Then type this to see a list of the distributions that are currently available:

```sh
wsl --list --online
```

You should get the following:

<img width="600" alt="Installation Screen" src="https://www.itprotoday.com/sites/itprotoday.com/files/WSL%201.jpg">

Now you will need to choose the distro you would like to use, I recommend Ubuntu.
To install the chosen distro  type the following: (replace Ubuntu the your distro of choice)

```sh
wsl --install -d Ubuntu
```

Now type the name of your distro in the command prompt: (for example Ubuntu)

```sh
Ubuntu
```

It will prompt you to enter a username and password, these will be exclusively for Ubuntu and do not need to match your computer credentials, etc.

Now you're set to go :)
