
## 1\.纹理操作


### 1\.1 重复、旋转、位移、缩放


重复


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318690.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318690.png)


但是要在水平方向上重复，还得允许


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318700.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318700.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318695.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318695.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318705.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318705.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318697.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318697.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318716.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318716.png)


按照刚才的重复方式


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318975.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318975.png)


**如果设置为镜像重复**


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318004.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318004.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318021.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318021.png)


**位移**


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318047.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318047.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318060.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318060.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318076.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318076.png)


**旋转**


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318276.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318276.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318288.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318288.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318298.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318298.png)


### 1\.2 翻转与alpha生成颜色


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318338.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318338.png)


正常的图


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318350.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318350.png)


**不翻转默认是翻转的**


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318403.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318403.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318479.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318479.png)


**预乘透明度**


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318537.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318537.png)


预先乘透明度


主要是会有一个描边的效果


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318552.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318552.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318577.gif)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318577.gif)


## 2\.纹理属性


### 2\.1 纹理过滤


比如一张原图很大，但是到3D场景中要变小，两个分辨率是不一样的


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318605.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318605.png)


**放大两种方法**


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318701.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318701.png)


第一种方式是最近邻


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318725.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318725.png)


直接取的是像素来放大


最近邻就是由原图附近去找然后模拟一些颜色


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318736.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318736.png)


设为线性，这个就比较光滑


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318757.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318757.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318864.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318864.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318898.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318898.png)


**缩小**


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318918.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318918.png)


最接近的像素，较粗糙


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318978.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318978.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318027.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318027.png)


线性，求平均


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318064.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318064.png)


但是这两种都还是有瑕疵，所以诞生了


**mipmap解决摩尔纹条纹**


mipmap原理是先算好缩小一倍的样子，再算缩小一倍的样子，再算，以此循环


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318085.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318085.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318267.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318267.png)


这是默认的方式


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318320.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318320.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318337.gif)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318337.gif)


注意这四种生成mipmap要开起，不然又会产生魔纹


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318411.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318411.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318427.gif)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318427.gif)


**剩下三种见上，无非就是性能消耗**


**各项异性anisotropy解决倾斜模糊问题**


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318464.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318464.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318487.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318487.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318575.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318575.png)


## 3\.jpg\_png\_webp\_dds\_ktx\_hdr\_exr格式纹理


同一个鱼眼图不同格式


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318605.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318605.png)


这些格式里面最小的是ktx2，最大是hdr，主要就是曝光不同，没有太大曝光要求，肯定越小越好


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318796.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318796.png)


### 3\.1 英伟达导出优化压缩


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318814.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318814.png)


打开软件，打开图片，正常第一步选择8bit，rgba


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318830.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318830.png)


也可以选择其他比如第二个就是hdr


右下角导出


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318840.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318840.png)


可选格式


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318852.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318852.png)


**后面用到可以回看视频教程**


### 3\.2 threejs中使用KTX2\_DDS\_TGA纹理


要使用ktx要导入加载器


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318867.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318867.png)


使用加载器要先实例化一个文件，文件位置在


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318003.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318003.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318089.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318089.png)


移动到public下面


导出为etx2图片最好采用编码


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318133.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318133.png)


**是否翻转图片，在导出时设置**


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318154.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318154.png)


因为设置代码会不起效果


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318289.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318289.png)


导出的时候如果点击了生成mipmap，那么久不能成为场景贴图，这句代码失去效果


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318309.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318309.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318366.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318366.png)


所以最好不勾选


**其他的图片就类似**


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318384.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318384.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318435.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318435.png)


### 3\.3设置高动态范围全景背景色调映射和色调曝光


这是针对于hdr图的


加载hdr


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318451.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318451.png)


背景色调


是给渲染器加


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318498.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318498.png)


值有


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318618.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318618.png)


第三个一般用于室外更柔和，四五个模拟电影质感


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318297.gif)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318297.gif)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318684.gif)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318684.gif)


曝光


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318676.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318676.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318743.gif)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318743.gif)


### 3\.4 高动态范围EXR\_TIF\_PNG加载使用


这三个都可以使用hdr的功能


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318679.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318679.png)


跨平台


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318733.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318733.png)


tif类似于hdr也可以调节曝光


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318643.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318643.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318848.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318848.png)


## 4\.材质深度模式


离相机远近叫做深度


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318901.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318901.png)


深度图用到的z\-buffer算法


**说白了深度效果就是为了在3D中实现遮挡效果**


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318056.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318056.png)


要完成深度，就需要两张图，一张绘制出来的渲染图，一张顺带用代码生成的深度图，那么两者结合深度图越白色的地方就会渲染的比较黑，实现阴影效果，深度越黑的地方实现遮挡效果


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318083.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318083.png)


深度设置有三种


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318485.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318485.png)


用在函数里面的有


**一般小于等于用的多**


输入像素就是渲染图，缓冲器就是深度图


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318565.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318565.png)


当前有两个平面


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318672.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318672.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318892.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318892.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318195.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318195.png)


不写入


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318354.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318354.png)


总是写入


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318385.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318385.png)


深度写入和深度测试代码


深度写入就是深度图会写入进来，虽然看不到但是存在于内存中


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318907.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318907.png)


深度测试就是检不检测深度，比如这里设置的是比他小就会被大的遮挡，这个红色要比有光的要大，那么从红色望过去按理说会遮挡住有光，那么此时不开启有光的深度测试，就不再检测深度，同时渲染比红色后渲染，那么就会看到此时深度不生效


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318954.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318954.png)


如果做深度测试


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318233.gif)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318233.gif)


## 5\.材质混合模式


混合模式可用值


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318057.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318057.png):[wgetcloud加速器官网下载](https://longdu.org)


设置混合模式，前面都是定义好的，只有最后一种自定义选择的时候，才能去选择blending下面的设置


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318514.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318514.png)


不混合


完全不透明，透明区域用白色覆盖


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318714.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318714.png)


additive


两个颜色直接相加，比如背景墙的黄色和平面的红色相加 ，白色加上任何颜色还是白色


**这种用在光上常见，两个光结合**


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318449.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318449.png)


目标颜色也就是背景减去原颜色也就是红色，那就是绿色


其他颜色减去白色都是黑色


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318904.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318904.png)


直接相乘


两个颜色相乘会得到一个更暗的颜色


透明乘任何都是白色


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318681.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318681.png)


剩下就是自定义


### 5\.1透明冰块透明液体透明杯子多个透明物体混合渲染


一个模型杯子


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318605.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318605.png)


里面是装有水的，但是外面看不见


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318660.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318660.png)


原因是水是透明的，透明跟玻璃混合有一些问题


加载模型微调数据


先渲染冰块再水再杯子


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318974.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318974.png)


隐藏杯子和水，把冰块材质变为透明


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318413.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318413.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318441.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318441.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318615.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318615.png)


显示水，发现冰块不见


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318882.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318882.png)


拿到水的材质，重新设置材质，并且为透明，透明度为0\.5


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318021.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318021.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318518.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318518.png)


**其原因就是这里没有设置混合，所以默认就是原先水的透明度就是1，很透明，和里面透明物体相乘就还是很透明1，那就完全看不到里面，所以如果要解决，就把水的透明度调低**


然后同样设置杯子材质透明度


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318570.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318570.png)


此时能够勉强看到水和冰块


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318044.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318044.png)


**第二种解决办法就是混合**


首先先把水混合调为自定义


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318389.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318389.png)


此时就可以gui去调节


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318678.gif)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318678.gif)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318933.gif)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318933.gif)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318590.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318590.png)


同理设置杯子


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318284.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318284.png)


## 6\.裁剪


### 6\.1 裁剪平面


比如现在有这个一个物体


这是一个


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318748.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318748.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318153.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318153.png)


裁剪是材质的属性，一共三个


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318150.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318150.png)


首先创建一个平面，这个平面是一个数学库，不会真正大小，第一个参数是什么位置，比如下面这个例子就是一个三围向量，但是平行于y轴


第二个参数就是与原点的距离


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318787.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318787.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318283.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318283.png)


然后设置材质的裁剪平面，并且在渲染器打开裁剪平面


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318533.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318533.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318768.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318768.png)


然后就可以通过设置刚才的两个属性，单独来设置就是这么设置，来达到一个裁剪的不同效果


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318558.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318558.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318226.gif)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318226.gif)


裁剪也可以创建多个裁剪平面放入数组


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318491.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318491.png)


第一个是平行于y轴，第二个是平行于x轴，也就是第一个右边，第二个上面会保留


而并集就是所有，也就是两个都满足的才会保留


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318374.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318374.png)


**默认的效果是并集，也可以交集，**但是交集就是各满足各的都可以保留[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318086.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318086.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318735.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318735.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318216.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318216.png)


### 6\.2 裁剪场景


裁剪场景就要用到渲染器的属性


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318814.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318814.png)


xy从什么地方开始，裁剪宽高多少


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318077.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318077.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318480.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318480.png)


**那么此时另外一边，就可以空出来去弄其他的场景，甚至相机都可以再来一个**


比如现在再来一个场景


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318175.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318175.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318417.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318417.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318764.gif)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022318764.gif)


## 7\.模板渲染


现在有一个平面一个球


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319450.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319450.png)


**现在实现一个效果，让小球只渲染在平面上，没了平面，就没了小球，这时候就需要平面作为一个模板**


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319843.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319843.png)


首先需要开启


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319702.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319702.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319050.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319050.png)


首先两个都要设置属性允许写入


然后在模板（平面处）设置mask代表者写入值允许范围多少


ref是一个基准值，模板和写入模板的应该保持一致，并且要在范围内


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319655.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319655.png)


然后是缓冲区判断，就是什么时候允许写入，这个值表示当他们相等时写入


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319345.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319345.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319052.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319052.png)


最后当深度值和缓冲都相等时，在模板处设置通过写入方式，固定的值


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319885.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319885.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319570.gif)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319570.gif)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319177.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319177.png)


### 7\.1 实现金属切割面


前面裁剪物体后，会发现裁剪到的区域是空心的，如果想要实心呢


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319762.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319762.png)


实现效果，创建平面，材质，注意属性metalness是金属度，roughness是粗糙度


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319520.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319520.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319901.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319901.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319500.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319500.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319998.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319998.png)


那现在就可以用到模板了，只要切面才显示


两个物体首先是里面这个物体


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319657.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319657.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319432.png)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319432.png)


[![](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319692.gif)](https://heymar.oss-cn-chengdu.aliyuncs.com/undefined202412022319692.gif)


  * [1\.纹理操作](#tid-C7Hyhk)
* [1\.1 重复、旋转、位移、缩放](#tid-5djtXH)
* [1\.2 翻转与alpha生成颜色](#tid-wmndhK)
* [2\.纹理属性](#tid-BrYD2k)
* [2\.1 纹理过滤](#tid-mm4YYd)
* [3\.jpg\_png\_webp\_dds\_ktx\_hdr\_exr格式纹理](#tid-b6zkMn)
* [3\.1 英伟达导出优化压缩](#tid-FpcXH4)
* [3\.2 threejs中使用KTX2\_DDS\_TGA纹理](#tid-etBTjy)
* [3\.3设置高动态范围全景背景色调映射和色调曝光](#tid-Yk45Mf)
* [3\.4 高动态范围EXR\_TIF\_PNG加载使用](#tid-48D8em)
* [4\.材质深度模式](#tid-KxFhXP)
* [5\.材质混合模式](#tid-dfWNRX)
* [5\.1透明冰块透明液体透明杯子多个透明物体混合渲染](#tid-8fD4Rt)
* [6\.裁剪](#tid-KJhCWs)
* [6\.1 裁剪平面](#tid-wSbDAM)
* [6\.2 裁剪场景](#tid-fXKX8z)
* [7\.模板渲染](#tid-y8hEet)
* [7\.1 实现金属切割面](#tid-EJNsyA)

   \_\_EOF\_\_

   ![](https://github.com/heymar)Heymar  - **本文链接：** [https://github.com/heymar/p/18582998](https://github.com)
 - **关于博主：** 评论和私信会在第一时间回复。或者[直接私信](https://github.com)我。
 - **版权声明：** 本博客所有文章除特别声明外，均采用 [BY\-NC\-SA](https://github.com "BY-NC-SA") 许可协议。转载请注明出处！
 - **声援博主：** 如果您觉得文章对您有帮助，可以点击文章右下角**【[推荐](javascript:void(0);)】**一下。
     
