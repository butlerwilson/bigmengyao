## 合成大梦瑶
合成大西瓜的粉丝版本(其实就是替换了部分图片)
11张所用的"水果"图片均为梦瑶粉丝群:652651723内成员的群头像
## 演示地址
合成大梦瑶 （手机端网页游戏，未适配pc端）
https://damengyao.ayano.top/
## 具体魔改方法
需要替换的地方有`loading图标`，`11个水果的图片`，`右上角转换水果的图标`
### loading图标（gif）
文件：/res/loading.gif
修改方法：同名gif文件替换

### 水果的图片
需要更改两个文件
文件1：/res/raw-assets/1b/1b81b7730.png
第3,4,5,6,7,8,10级水果就在这张图内

文件2：/res/raw-assets/18/18858a142.png
第11,9,2,1级水果就在这张图内

修改方法：建议使用ps将两张图片内的11个圆形路径抠下来并保存，再将自己需要替换的图片分别导入ps并用相应路径进行剪切，替换原来的"水果"
最终导出为png图片，命名同样与原文件一致

### 转换水果的图标
需要更改两个文件
文件1：/res/raw-assets/1b/cc/cc9eb6c6-89f1-4f53-9b48-5fb7483f860e.png
文件2：/res/raw-assets/1b/f0/f0dcc758-76c1-4afd-8efc-f65e609431d0.png
修改方法：替换的图片建议长宽都不超过200像素，两个位置的文件可以一样，仅需更改为不同名字
