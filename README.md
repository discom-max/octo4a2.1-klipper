octo4a2.1安装klipper文件与不正常的处理方法。
/mnt/external/extensions/klipper/start.sh
#修改如下
nginx
LD_PRELOAD=/home/octoprint/ioctl-hook.so /root/klipper-venv/bin/python $KLIPPER_ARGS &
LD_PRELOAD=/home/octoprint/ioctl-hook.so /root/moonraker-venv/bin/python $MOONRAKER_ARGS
