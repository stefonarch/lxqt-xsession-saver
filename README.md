# lxqt-xsession-saver


>X11 session saver module for the LXQt Desktop.

* Restores windows from the last session and their positions on their workspaces after login.
* Saves every 3 minutes the actual session.

Based on [sessionctrl](https://github.com/christarazi/sessionctrl/).

### Installation and Usage

* Install `xprop ` and `wmctrl`.
* Save `lxqt-sessionsaver` script somewhere in your $PATH and make sure it's executable.
* Save `xsessionsaver.desktop` to `/etc/xdg/autostart`.
* Save  `sessionctrl.py` to `/usr/share/lxqt/xsessionsaver-module/sessionctrl.py`


Restart your session.
As every other module it can be disabled or restarted in Session Settings.
A restart will restore the last saved session.

* You can blacklist and replace apps editing `$HOME/.config/sessionctrl`, see [Additional information](https://github.com/christarazi/sessionctrl#additional-information).






