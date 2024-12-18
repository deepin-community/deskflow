% deskflow-client(1) | User Commands
%
% "October 12 2024"

# NAME

deskflow-client - Mouse and keyboard sharing utility

# SYNOPSIS

**deskflow-client** [--address \<address\>] [--yscroll \<delta\>] [--sync-language] [--invert-scroll] [--host] [--display \<display\>] [--no-xinitthreads] [--use-x-window] [--daemon|--no-daemon] [--name \<screen-name\>] [--restart|--no-restart] [--debug \<level\>] \<server-address\>

# DESCRIPTION

Deskflow is a free and open source keyboard and mouse sharing app
formerly known as Synergy Community Edition.

**deskflow-client** is client side program of **deskflow**.

It connect to the Deskflow mouse/keyboard sharing server.

This manual page was written for the Debian distribution because the
original program does not have a manual page.

# OPTIONS

**-a**, **\-\-address** \<address\>
:   local network interface address.

**-d**, **\-\-debug** \<level\>
:   filter out log messages with priority below level.  level may be:
    FATAL, ERROR, WARNING, NOTE, INFO, DEBUG, DEBUG1, DEBUG2

**-n**, **\-\-name** \<screen-name\>
:   use screen-name instead the hostname to identify this screen in the configuration.

**-1**, **\-\-no\-restart**
:   do not try to restart on failure.

**\-\-restart**
:   restart the server automatically if it fails.

**-l**, **\-\-log** \<file\>
:   write log messages to file.

**\-\-no\-tray**
:   disable the system tray icon.

**\-\-enable\-crypto**
:   enable TLS encryption.

**\-\-tls\-cert**
:   specify the path to the TLS certificate file.

**\-\-yscroll** \<delta\>
:   defines the vertical scrolling delta, which is 120 by default.

**\-\-sync\-language**
:   enable language synchronization.

**\-\-invert\-scroll**
:   invert scroll direction on this computer.

**\-\-host**
:   act as a host; invert server/client mode and listen instead of connecting.

**\-\-display** \<display\>
:   when in X mode, connect to the X server at \<display\>

**\-\-no-xinitthreads**
:   do not call XInitThreads()

**\-f**, **\-\-no-daemon**
:   run in the foreground.

**\-\-daemon**
:   run as daemon.

**\-h**, **\-\-help**
:   display this help and exit.

**\-\-version**
:   display version information and exit.

# BUGS

See https://github.com/deskflow/deskflow/issues

# SEE ALSO

**deskflow**(1), **deskflow-server**(1)

# AUTHOR

HAYASHI Kentaro <kenhys@xdump.org>
:   Wrote this manpage for the Debian system.

# COPYRIGHT

Copyright © 2024 HAYASHI Kentaro

This manual page was written for the Debian system (and may be used by
others).

Permission is granted to copy, distribute and/or modify this document under
the terms of the GNU General Public License, Version 2 or (at your option)
any later version published by the Free Software Foundation.

On Debian systems, the complete text of the GNU General Public License
can be found in /usr/share/common-licenses/GPL.
