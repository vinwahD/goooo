# 一、功能说明

只需要十分钟，用30s~1min的音频，就能使用 AI 克隆出你想要的声音，从环境部署到训练完成，一键式操作，十分钟就能搞定。

注意：我做的一键训练，目前只支持中文。

# 二、视频教程

[https://www.bilibili.com/video/BV1WC411W79t](https://www.bilibili.com/video/BV1WC411W79t)

# 三、运行方法

1、打开 run.ipynb

点击运行->运行所有单元格，启动程序，自动配置环境，开启服务。

![img](./images/0.png)

2、打开输出的 public URL

![img](./images/1.png)

3、根据你的音频选择数据类型

![img](./images/2.png)

4、点击开始训练

点击可以在前台看到运行到哪一步了，在后台也能看到日志输出

![img](./images/3.png)

![img](./images/4.png)

5、打开 api 地址

当前端显示正在开启预测后

![img](./images/5.png)

打开 API 地址：

![img](./images/6.png)

6、声音克隆

选择训练好的模型，然后输入文本，就可以愉快地玩耍了。

![img](./images/7.png)

## 四、自定义音频

1、找到数据集，创新新数据集

![img](./images/8.png)

2、上传音频数据

![img](./images/9.png)

3、修改配置并启动

![img](./images/10.png)

4、绑定了一个新的 input 地址

![img](./images/11.png)

5、打开工作空间

这样在右边的侧边栏里就能看到新绑定的数据集了。

![img](./images/12.png)

6、训练填写新绑定的地址

![img](./images/13.png)
