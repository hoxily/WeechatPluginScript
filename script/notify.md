# 脚本意图
此脚本需要与Notify接收端配合使用，才能起到提醒功能。
脚本修改自 magnific0 的 anotify.py，见 [anotify.py](http://weechat.org/scripts/source/anotify.py.html/)
# 现有BUG
- Python中的threading是伪多线程，脚本中的sending_thread不能即时检测到sending_queue中插入了新元素。
