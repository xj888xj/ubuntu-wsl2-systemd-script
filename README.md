ubuntu-wsl2-systemd-script

Script is unsupported and will no longer be maintained, but will be up here because it is used by quite some people.

脚本不受支持，将不再维护，但会在这里，因为它被相当多的人使用。

Script to enable systemd support on current Ubuntu WSL2 images from the Windows store.

用于在 Windows 应用商店中的当前 Ubuntu WSL2 映像上启用 systemd 支持的脚本。

I am not responsible for broken installations, fights with your roommates and police ringing your door ;-).

我不对损坏的装置、与室友的争吵和警察敲门负责;-）。

Instructions from the snapcraft forum turned into a script. Thanks to Daniel on the Snapcraft forum!

snapcraft论坛上的说明变成了一个脚本。感谢 Snapcraft 论坛上的 Daniel！

Usage 用法

You need git to be installed for the commands below to work. 

您需要 git 安装以下命令才能正常工作

sudo apt install git

Run the script and commands
运行脚本和命令

git clone https://github.com/DamionGans/ubuntu-wsl2-systemd-script.git

cd ubuntu-wsl2-systemd-script/

bash ubuntu-wsl2-systemd-script.sh

# Enter your password and wait until the script has finished

Then restart the Ubuntu shell and try running systemctl

然后重新启动 Ubuntu shell 并尝试运行 systemctl

systemctl

If you don't get an error and see a list of units, the script worked.

如果您没有收到错误并看到单位列表，则该脚本有效。

Have fun using systemd on your Ubuntu WSL2 image. You may use and change and distribute this script in whatever way you'd like.

在 Ubuntu WSL2 映像上使用 systemd 玩得开心。您可以以任何您喜欢的方式使用、更改和分发此脚本。
