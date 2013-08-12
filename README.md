# GMailinator

Adds Gmail-esque keyboard shorcuts to Mail.app.  This is still very much a work
in progress.

## Supported Shortcuts


## How to install

1. Grab the latest build from the builds/ directory, and unzip to ~/Library/Mail/Bundles
2. Enable Mail.app plugins:
       `defaults write com.apple.mail EnableBundles -bool true`

## How to build

1. Load up the project in Xcode.
2. Run the build, this should automatically create ~/Library/Mail/Bundles (but you may need to create this).
3. Enable Mail.app plugins:
       `defaults write com.apple.mail EnableBundles -bool true`
4. Relaunch Mail.

## Credits

A lot of this was built with heavy use of of the
[BindArchiveToDelete](https://github.com/benlenarts/BindDeleteKeyToArchive)
project by Ben Lenarts.  The Xcode project and interface skeleton were
all from that project, and for the most part, renamed.  I added the keybinding code.

Other references:

- [Rui Carmo's PyObjC vim keybinding script](http://taoofmac.com/space/blog/2011/08/13/2110)