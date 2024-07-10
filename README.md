# Nasa Wallpapers For Trinity DE
This enables nasa wallpapers on debian with Trinity DE.  
(this is based on my other script, bingwallpaper.sh , here: https://github.com/seb3773/bing-wallpapers-for-linux_tde )

## Description
nasawallpaper.sh is a simple script that retrieves 'Nasa image of the day' and set it as current wallpaper. It is designed for Trinity DE.  
You can run it 'singleshot' by just executing the script without arguments, run it as a daemon (-d), or add it to cron jobs (-c).  
  
You can put the script anywhere, but I recommend the folder /usr/local/bin so it will be available for all users as a direct command.  
  
## Settings
You can set the check interval in daemon/cronjob mode (-i); don't forget the image is renewed only once a day, so depending of your usage it's maybe not usefull to set a too short interval.  
You can specify too the folder where images will be downloaded (-f); if it doesn't exist yet, it will be created if possible.  
  
  
Usage:  
 "nasawallpaper.sh"       run and exit  
 "nasawallpaper.sh -d"    run as daemon  
 "nasawallpaper.sh -k"    kill daemon  
 "nasawallpaper.sh -c"    add task to cron  
 "nasawallpaper.sh -r"    remove task from cron  
 "nasawallpaper.sh -i"    set check interval  
 "nasawallpaper.sh -f"    set wallpapers download folder  
 "nasawallpaper.sh -p"    display status/settings  
 "nasawallpaper.sh -h"    help  
  
  
+-----------------------+
