# Mainsail_Theme
V1 Engineering Themed Mainsail Interface


## To Install

SSH in,

```
cd ~/
git clone https://github.com/V1EngineeringInc/Mainsail_Theme.git
bash ~/Mainsail_Theme/install.sh
```

### Add this to moonraker.conf to get updates
```
[update_manager client V1Theme]
type: git_repo
path: ~/Mainsail_Theme
origin: https://github.com/V1EngineeringInc/Mainsail_Theme.git
install_script: install.sh
is_system_service: False
```
