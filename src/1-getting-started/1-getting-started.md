Git thinks about its data more like a stream of snapshots.

The mechanism that Git uses for this checksumming is called a SHA-1 hash. This is a 40-character string composed of hexadecimal characters (0–9 and a–f) and calculated based on the contents of a file or directory structure in Git. A SHA-1 hash looks something like this:
```24b9da6552252987aa493b52f8696cd6d3b00373```

Git has three main states that your files can reside in: modified, staged, and committed.

Install on Linux

```

$ sudo dnf install git-all

Or

sudo apt install git-all

```

Installing from Source

```

$ sudo dnf install dh-autoreconf curl-devel expat-devel gettext-devel \
  openssl-devel perl-devel zlib-devel
$ sudo apt-get install dh-autoreconf libcurl4-gnutls-dev libexpat1-dev \
  gettext libz-dev libssl-dev

# For documentation

$ sudo dnf install asciidoc xmlto docbook2X
$ sudo apt-get install asciidoc xmlto docbook2x

```

Git comes with a tool called git config that lets you get and set configuration variables that control all aspects of how Git looks and operates.

You can view all of your settings and where they are coming from using:

```
$ git config --list --show-origin
```

Your identity

```
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```

Your editor

```
$ git config --global core.editor emacs
```

Your default branch name

```
$ git config --global init.defaultBranch main
```

Checking Your Settings

```
$ git config --list
$ git config user.name
```

Git help

```
$ git help <verb>
$ git <verb> --help
$ man git-<verb>
```



