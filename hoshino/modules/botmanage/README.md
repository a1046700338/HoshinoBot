# bot群管功能
> 目前支持的功能有：
>
> - 帮助
> - 广播
> - 退群、加群
> - ls服务管理

## Hoshino的来杯咖啡回复功能

> Mac 和 Windows 都测试过没问题！
>

![预览图](https://user-images.githubusercontent.com/25716090/190124786-913a51c3-b218-4421-8114-aa681c26254b.png)



## 安装教程

1. 用项目中`feedback.py`将`HoshinoBot/hoshino/modules/botmanage/feedback.py`替换。

4. 完成后重启Hoshino即可！

   

## 命令

- 来杯咖啡 +问题

- 在反馈信息后面加#并接你要回复的内容即可(能带图片)

  ![使用方法](https://user-images.githubusercontent.com/25716090/190124916-e1e9419a-6de8-45d5-a3c5-665a7b19de0b.png)
  
- 也支持使用QQ的reply进行回复，此时不需要带#
   
  ![使用方法](https://user-images.githubusercontent.com/25716090/190539637-c0704923-2ec6-4b2d-82fe-7cbdcb21378c.png)
  
   - 需要修改go-cqhttp配置，将下述key设置为true
   ```yml
   # 为Reply附加更多信息
     extra-reply-data: true
   ```



## 参考

- [Ice-Cirno/HoshinoBot](https://github.com/Ice-Cirno/HoshinoBot)
- [pcrbot/authMS](https://github.com/pcrbot/authMS)



## 已知问题&一些想法

- ~~关于给用户发的信息后面"作出以下回应"，这里是用回应还是回复好一些呢...QAQ~~
- ~~想用回复功能做交互的，但是太菜了(有没有大佬啊啊啊！！！)~~
- 已实现回复交互，存在冲突可能性，希望有更好的解决方案
