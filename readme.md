## a simple scaffolding

为了可以全局使用命令,必须在package.json中配置
```
 "bin": {
    "watermelon": "bin/watermelon"
  },
```
然后执行npm link

chalk 
>修改控制台中字符串的样式（字体样式加粗等／字体颜色／背景颜色）