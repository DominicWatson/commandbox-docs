# Installation

Regardless of where you place the **box** binary, the first time you execute
it, a `.CommandBox` folder will be created in your user's home
directory and CommandBox will be extracted into that location. If you
delete this directory, it will be replaced the next time the CommandBox
executable is run.

## <i class="fa fa-windows"></i> Windows

Unzip the executable **box.exe** and just double click on it to open the
shell. When you are finished running commands, you can just close the
window, or type `exit`.

>**Hint**: You can make the `box.exe` available in any Windows
terminal by adding its location to the **PATH** system environment
variable. See http://www.computerhope.com/issues/ch000549.htm


## <i class="fa fa-apple"></i><i class="fa fa-linux"></i> Mac/\*Unix

### Manual Installation

Unzip the binary **box** and just double click on it to open the shell terminal.
When you are finished running commands, you can just close the window,
or type `exit`.

>**Hint**: You can place the binary in your `/usr/bin` directory so it can
be available system-wide via the `box` command in any terminal
window.

### Homebrew (Mac)

[Homebrew](http://brew.sh) is a great Mac package manager, it can easily install and keep
your CommandBox installation up to date (even binary releases), just run the following:

```bash
brew install https://github.com/Ortus-Solutions/commandbox/raw/master/build/commandbox.rb
```

>**Info**: Once we reach stable version, we will be submitting CommandBox to the
Homebrew Binary Tap, for even easier installation.

## Linux (Redhat)

After you have downloaded the `commandbox.rpm` file, install it using the `rpm`
command.

```bash
rpm –ivh commandbox-rpm-1.0.0.rpm
```

Run the `box` binary to begin the one-time unpacking process.

## Linux (Debian)

After you have downloaded the `commandbox.deb` file, install it using the `dpkg`
command.

```bash
sudo dpkg -i commandbox-debian-1.0.0.deb
```

Run the `box` binary to begin the one-time unpacking process.

  [1]: http://www.computerhope.com/issues/ch000549.htm