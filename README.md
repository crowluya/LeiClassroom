# LeiClassroom
雷课堂
## 第一课:预览和规划
不用第三方库

项目有一漏洞或问题
    老师是服务器
    学生是客户端

音频
声音是一个数组

    PcmFromAudioDevice()
    PlayPcm()

视频

    ScreenImage(x,y,w,h)
    WindowImage()
    WindowList()

网络

    GuaNet.send()
    GuaNet.recv()

UI


写代码的方法

```

while(true){
    Time *t = GuaTime.now()
    GuaImage *img = ScreenImage(x, y, w, h)
    vector<GuaNet.Connetction> conns;
    for (c in conns) {
        GuaNet.send(c, img,data());
    }
    GuaTime.sleep(1000, t);
}
```

# 怎样高效学习 C++ 语言

1. 入门课
2. 用c++重写入门
3. 领域知识

## vscode cpp 环境搭建

```
https://www.jianshu.com/p/090a6516d9e1

``

