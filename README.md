记录pc被黑的日常

## 第一天

卧槽，发现电脑被黑了，被人拿去挖矿，我说咋为啥电脑风扇天天呼呼的，闲话少说，上图

![JT@)BKJBI60 ER}D185FNSG](https://user-images.githubusercontent.com/1182593/168197101-8cf034a1-4e03-41ea-a3f8-36f3f75ad072.png)

伪装成sshd进程，这台电脑估计是废了，先把进程干掉，git用户相关的程序只有gitlab，反正也没啥用，删掉完事

```
sudo gitlab-ctl stop
sudo apt-get remove gitlab-ce
```

暂时想不出有啥办法对抗黑客的，也没什么重要的东西，先暂时这样吧，顺便看看黑客的手段，学习学习

# 大家有啥建议和意见，欢迎提issue
