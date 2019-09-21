A renovation of [mReXiTuS's custom css](https://github.com/mReXiTuS/tomato-design). 
Modified to be more condensed and compatible with Fresh Tomato.

## Now with Icons

## Screenshots
Dark Theme
![Screenshot](https://raw.githubusercontent.com/theredhood13/tomato-css-dark/master/Screenshot_dark.png)
Light Theme
![Screenshot](https://raw.githubusercontent.com/theredhood13/tomato-css-dark/master/Screenshot_light.png)

## Installation

### Using init script (recommended)

#### 1. Upload script
1. Navigate to __Administration__ > __Scripts__
1. Choose __WAN Up__
1. Paste the contents of [tomato_wanup_dark](https://github.com/theredhood13/tomato-css/blob/master/tomato_wanup_dark) or [tomato_wanup_light](https://github.com/theredhood13/tomato-css/blob/master/tomato_wanup_light)
1. In case your router doesn't use WAN (access point, etc.) try the firewall script instead [tomato_firewall_dark](https://github.com/theredhood13/tomato-css/blob/master/tomato_firewall_dark)/[tomato_firewall_light](https://github.com/theredhood13/tomato-css/blob/master/tomato_firewall_light) _solution from u/brantot_
1. Save changes

#### 2. Enable Custom CSS
1. Navigate to __Administration__ > __Admin Access__
1. Change color scheme to __custom.css__
1. Save changes and reboot router
1. You must erase your browser's cache before the new UI appears.

_Tested and working on a Netgear R8000 router running FreshTomato 2019.2_

### Using SSH

#### 1. Upload Custom CSS over SSH
1. Enable SSH deamon in __Administration__ > __Admin Access__
2. Connect to router over SSH
3. Create folder __wwwext__ in __/var/__
4. Upload custom.css file into __/var/wwwext/__

#### 2. Enable Custom CSS
1. Navigate to __Administration__ > __Admin Access__
1. Change color scheme to __custom.css__
1. Save changes and reboot router
1. You may need to erase your brower's cache before the new UI appears.

_If using SSH method, you must repeat the steps on reboot. Router will automatically remove custom.css file after reboot._
