% deskflow(1) | User Commands
%
% "October 12 2024"

# NAME

deskflow - Mouse and keyboard sharing utility

# SYNOPSIS

**deskflow**

# DESCRIPTION

Deskflow is a free and open source keyboard and mouse sharing app
formerly known as Synergy Community Edition.

Use the keyboard, mouse, or trackpad of one computer to control nearby
computers, and work seamlessly between them.

Deskflow is oriented cross-platform and supports all major operating
systems, including Windows, macOS, Linux, and Unix-like BSD-derived
which supports Wayland and has kindly configuration wizard feature
because it is also upstream of commercial fork of Synergy and it can
be expected continuous maintenance somewhat. 

Deskflow provides similar UI like Barrier so transition to Deskflow is easy.

This manual page was written for the Debian distribution because the
original program does not have a manual page.

# OPTIONS

**deskflow** has no options and it spawns **deskflow-server** or **deskflow-client**.

See **deskflow-server**(1) or **deskflow-client**(1) in details.

# FILES

${HOME}/.config/Deskflow/deskflow-server.conf
:   The per-user configuration file to control the behaviour of
    deskflow server.

# BUGS

See https://github.com/deskflow/deskflow/issues

# SEE ALSO

**deskflow-server**(1), **deskflow-client**(1)

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
