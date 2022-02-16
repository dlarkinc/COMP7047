
# FileZilla

![GitHub last commit](https://img.shields.io/github/last-commit/dlarkinc/soft8023-darts-03)
[![APM](https://img.shields.io/apm/l/vim-mode)](https://github.com/dlarkinc/soft8023-darts-03/blob/master/LICENSE)
![GitHub contributors](https://img.shields.io/github/contributors/dlarkinc/soft8023-darts-03)
[![Twitter URL](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Ftwitter.com%2FFileZillaPro%3Fref_src%3Dtwsrc%255Egoogle%257Ctwcamp%255Eserp%257Ctwgr%255Eauthor)](https://twitter.com/FileZillaPro?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor)

This is the development home for FileZilla, a libre file transfer client for macOS and Windows. Command line interface (CLI) for Linux, macOS and Windows. The core libraries are used in [FileZilla](https://twitter.com/FileZillaPro?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor).

<img src="https://pbs.twimg.com/profile_banners/1025316688131235841/1591956796/1500x500"/>


## Source
Source code is available licenced under the [AGPL License](https://www.gnu.org/licenses/agpl-3.0.en.html). 
**Pull requests welcome!**

## Localizations
Translations to new languages are welcome. Current available localizations are:
- _English_,
-  _Czech_,
-  _Dutch_, 
- _Finnish_, 
- _French_,
-  _German_, 



## Support & Documentation
For general help about using Filezilla, please refer to the [documentation](https://wiki.filezilla-project.org/Documentation).

## Installation and Setup

-   Prerequisites: 25MB of space free on your drive and administrator privileges.
-   Download FileZilla Server from FileZilla website
-   Locate the installer in your download folder and run it
-   Confirm you allow FileZilla Server to make changes to your device
-   Accept the  [AGPL license](https://www.gnu.org/licenses/agpl-3.0.en.html)  terms, the terms under which FileZilla Server is offered
-   Select what to install (Server, Admin interface, desktop icons, shortcuts)
-   To decide where to install by clicking Browse, otherwise click Next
-   To add the icons for FileZilla Server choose a Start menu folder or create one
-   FileZilla Server is installed as a  [Windows Service](https://en.wikipedia.org/wiki/Windows_service), you can start it manually if you want
-   Set the port on which FileZilla Server will listen to connections from the Admin interface
-   Choose a password and enter it twice to confirm it
-   By default the Admin interface will start up automatically, you can deselect that option
-   The installation is complete, now you can start configuring FileZilla Server
-   Create a user and/or group with permissions to one or more mount point (mount points include a virtual path and a native path)
-   You can now use FileZilla Server, select ‘Configure’ menu item to set other elements

### Installation
```shell		
$sudo apt-get update
$sudo apt-get install filezilla
```