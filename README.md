# 关于
这个efi修改自 https://github.com/Z0KRI/Dell-Inspiron-5391-Hackintosh 这个大佬的

序列号之类的在更新前改过，不过最好还是自己再改一遍

**仅在macos13.7.8测试通过**

**OC版本为1.0.4**

#### 废话：
目前还是以13为准，更的比较慢一般我遇见bug修好了就会更，后面可能会开坑12或者14
### 修改内容
#### 2025.8.23更新
- 补全更多频段
- 修改alcid为99（解决了kernel_task占用高和有线耳机只有电流声）
- 更新部分kext

#### 第一版
- 修改smbios为macobookair9,1（2020）
- 补全部分cpu频段
- 添加无线网卡驱动
- 触摸板从轮询改为中断

### BUG和不能用的
- **独显（MX250）**
- **麦克风**
- 隔空投送和投屏
- typec口插部分U盘可能会没有反应
- 屏幕色彩疑似有点问题有时候会过曝
- 蓝牙耳机无法播放apple music
- 音质可能没windows好

### 截图
![](https://youke1.picui.cn/s1/2025/08/23/68a9c38539b77.png)

![](https://youke1.picui.cn/s1/2025/08/23/68a9c3865ec9d.png)