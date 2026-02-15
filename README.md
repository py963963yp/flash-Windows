# Running Windows on the Xiaomi Mi 9


## ⚠️ Warning
We're not responsible for bricked devices, missing recovery partitions, dead xiaomi factoryline ~~workers~~ cowboys, dead microSD cards, dead pmics, dead ram, dead display ics, dead cpus, any xiaomi/poco shenanigans, dead cats or dogs, nuclear wars or you getting fired because you forgot to boot back into android for the alarm.

All the files here have been contributed by other users, here you will find a guide with the working files we managed to get. This is a delicate process, do it under your own risk and follow all the steps carefully.

**IF YOU AREN'T COMFORTABLE MODDING YOUR PHONE OR ITS PARTITION TABLE OR YOU ARE PARANOID OF BRICKING YOUR DEVICE CLICK AWAY NOW!!! YOU HAVE BEEN WARNED, YOU ARE ON YOUR OWN IF YOU BRICK YOUR DEVICE!!! AGAIN! YOU HAVE BEEN WARNED!!!**

> This flashing will erase data

### Installing Windows
> install recovery
Use recovery that can decrypt data
- [Recommend Modified recovery](https://github.com/n00b69/woa-cepheus/releases/tag/Recovery)
> enter recovery
```cmd
adb reboot recovery
```
```cmd
or Manually reboot the phone to recovery
```
> download Windows and recovey rom
- [Windows on ARM image（have drivers）](https://www.123912.com/s/lGrLjv-hgFk)
- [recovery rom](https://github.com/py963963yp/flash-Windows/releases/tag/v1)

> change recovery rom and type what allocate of storage

```cmd
unzip 安装.zip
cd tools
vi flash.sh
```
按照flash.sh中注释修改，先按i开启编辑模式后修改，然后按ESC后输入：wq保存退出

> install Windows
```cmd
rm 安装.zip 
zip -r install.zip *
```
然后回到recovery安装界面安装
