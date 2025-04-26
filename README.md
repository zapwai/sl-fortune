# sl-fortune
Slack Fortune (Display a fortune to your desktop with some Slackware flair)

https://zapwai.net/sl-fortune

sl-fortune (a fortune notification in X with a slack-ish icon)

sl-fortune (Slack Fortune) calls fortune and sends the output to
your desktop via notify-send. Three slack-themed icons are provided.

When run as root the icon can be set to one of {tux, bob, slk}.

`#sl-fortune bob`

sl-fortune can autostart if a user runs it with the --install flag.

`$sl-fortune -i`

It has a random delay on start by default, or when run with the -r flag

`$sl-fortune -r`

(To disable this, remove the -r flag in ~/.config/autostart/sl-fortune.desktop)

The image of J.R. "Bob" Dobbs is a trademark of The SubGenius Foundation, Inc.

Visit http://www.subgenius.com for the good word from the Living Slack Master.

sl-fortune v0.1, copyright (c) 2021 David Ferrone

May be freely distributed under the terms of the GNU General Public License v2.0