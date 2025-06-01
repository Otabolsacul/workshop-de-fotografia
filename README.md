# This is an example Hyprland config file.
# Refer to the wiki for more information.
# https://wiki.hyprland.org/Configuring/

# Please note not all available settings / options are set here.
# For a full list, see the wiki

# You can split this configuration into multiple files
# Create your files separately and then link them to this file like this:
# source = ~/.config/hypr/myColors.conf


################
### MONITORS ###
################
monitor=DP-3,1920x1080@200,0x0,1
monitor=eDP-1,disable
monitor=,preferred,auto,1

# See https://wiki.hyprland.org/Configuring/Monitors/


###################
### MY PROGRAMS ###
###################

# See https://wiki.hyprland.org/Configuring/Keywords/

# Set programs that you use
$terminal = kitty
$fileManager = dolphin
$menu = wofi --show drun


#################
### AUTOSTART ###
#################

# Autostart necessary processes (like notifications daemons, status bars, etc.)
# Or execute your favorite apps at launch like this:
exec-once = wl-wallpaper -o DP-4 "/home/otabolsacul/Downloads/PIXEL_CREATION_20240908_112340884.PORTRA>

# exec-once = $terminal
# exec-once = nm-applet &
# exec-once = waybar & hyprpaper & firefox
#############################
### ENVIRONMENT VARIABLES ###
#############################

^G Ajuda      ^O Gravar     ^F Onde está? ^K Recortar   ^T Executar   ^C Local      M-U Desfazer
^X Sair       ^R Ler o arq  ^\ Substituir ^U Colar      ^J Justificar ^/ Ir p/ linhaM-E Refazer
