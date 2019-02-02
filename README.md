# i3config Basic config to on LinuxMint Distribution

Currently installed Cinnamon19.1

## Following add packages needed
`apt-get install -y feh i3blocks terminator i3lock suckless-tools i3status pavucontrol xbacklight acpi sysstat  
i3config`

For the brightness keys on my Lenovo Laptop, I needed the following config (taken from https://stackoverflow.com/questions/39570979/setting-the-shortcut-keys-for-brightness-in-ubuntu-16-04-i3wm/46069318#46069318):

copy xorg.conf.d/* /usr/share/X11/xorg.conf.d/

## Battery i3blocks scripts
As in my laptop are two batteries, I adjusted the normal battery block script and made parameterized