#!/bin/sh

pgrep picom>/dev/null &&
   killall picom &>/dev/null ||
   setsid picom --config ~/.config/picom/picom.conf & >/dev/null
