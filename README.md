A renovation of [mReXiTuS's custom css](https://github.com/mReXiTuS/tomato-design). 
Modified to be more condensed and compatible with Fresh Tomato.

## New Version 2 Beta

## V2 Screenshots
#Coming Soon

## V1 Screenshots
Dark Theme
![Screenshot](https://raw.githubusercontent.com/theredhood13/tomato-css-dark/master/Screenshot_dark.png)
Light Theme
![Screenshot](https://raw.githubusercontent.com/theredhood13/tomato-css-dark/master/Screenshot_light.png)

## Installation

### Using Tomato Theme Base (easiest method)

1. Navigate to `Administration` > `Admin Access`
1. Choose theme from TTB
1. In theme name type `advanced_v1_dark` or `advanced_v1_light`

### Using init script (receives updates first)

#### 1. Upload script
1. Navigate to `Administration` > `Scripts`
1. Choose `WAN Up`
1. Paste the contents of [tomato_wanup_dark](https://github.com/theredhood13/tomato-css/blob/master/tomato_wanup_dark) or [tomato_wanup_light](https://github.com/theredhood13/tomato-css/blob/master/tomato_wanup_light)
1. In case your router doesn't use WAN (access point, etc.) or if you have problems using WAN Up, try the firewall script instead [tomato_firewall_dark](https://github.com/theredhood13/tomato-css/blob/master/tomato_firewall_dark)/[tomato_firewall_light](https://github.com/theredhood13/tomato-css/blob/master/tomato_firewall_light) (paste in __Firewall__ not WAN Up) _solution from u/brantot_
1. Save changes

#### 2. Enable Custom CSS
1. Navigate to `Administration` > `Admin Access`
1. Change color scheme to `custom.css`
1. Save changes and reboot router
1. You must erase your browser's cache before the new UI appears.

_Tested and working on a Netgear R8000 router running FreshTomato 2019.2_

### Using SSH

#### 1. Upload Custom CSS over SSH
1. Make sure SSH is enabled in `Administration` > `Admin Access`
2. Connect to router over SSH
3. Create folder `wwwext` in `/var/`
4. Upload custom.css file into `/var/wwwext/`

#### 2. Enable Custom CSS
1. Navigate to `Administration` > `Admin Access`
1. Change color scheme to `custom.css`
1. Save changes and reboot router
1. You may need to erase your brower's cache before the new UI appears.

_If using SSH method, you must repeat the steps on reboot. Router will automatically remove custom.css file after reboot._
