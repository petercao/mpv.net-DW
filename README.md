# mpvnet_DW
Forked from hooke007/mpv.net_CM
# 简介
mpvnet_DW：mpv.net_CM的个人定制版

mpv.net_CM：mpv.net的中文分支模组

mpv.net：基于mpv开源播放器的Windows媒体播放器

# DW版本特点
基于上游，做出以下个人定制款
1. 修改播放界面为ModernX（cyl0/ModernX）

2. 集成缩略图引擎thumbfast（po5/thumbfast）

3. 集成旧版懒人包里的SVP补帧插件（hooke007/MPV_lazy）

4. 修改右键菜单   
    • 修改部分翻译（参考potplayer）    
    • 修改排列顺序    
    • 修改预设组的vs滤镜和着色器方案，兼容更多显卡 
		
5. 修改部分mpv设置   
    • 默认硬件解码为auto-copy  
    • 默认音量为100  
    • 默认开启interpolation  
    • 默认模糊识别音频与字幕  
    • 不显示mpv.net的logo和特别版logo（否则会闪现原始logo）  
		
6. 修改部分快捷键设置（参考potplayer，用习惯了）  
    • 文件详细信息 — TAB  
    • 打开字幕 — l  
		
7. 更新libmpv-2.dll（20230212）

8. 自解压安装包封装

9. 一些其他细节

# 上游版本特点
引用自hooke007/mpv.net_CM

mpv.net_CM：

• 界面汉化   
• 编辑器选项修改   
• 菜单条目+初始快捷键修改   
• 集成Python+VapourSynth便携式组件   
• 预设脚本与着色器   
• 操作习惯移植自 mpv-lazy   
• 有更友好的界面操作性

mpv.net：   

• 几乎所有mpv的功能都可用，除去一些窗口行为  
• 兼容几乎所有mpv脚本/着色器，除去部分具有特定依赖的项目  
• 单实例/多实例切换   
• 支持基础操作的播放列表、音轨字幕轨列表面板   
• 图形化的设置修改与快捷键编辑器  
• 可自定义的右键菜单  
• 音量、窗口尺寸的退出时记忆 

# 预览
• 播放预览  

![播放预览](https://user-images.githubusercontent.com/125502871/219909389-0b85a976-0ef6-49c5-93b0-427d32eea67b.jpg)

• 右键菜单  

![右键菜单](https://user-images.githubusercontent.com/125502871/219910110-2c5347f5-65e8-49f4-bfa3-2f8dfbbe9723.jpg)

• 设置界面

![设置界面](https://user-images.githubusercontent.com/125502871/219910359-11ac16f3-7eeb-4d65-8075-3320ffd9f0d8.jpg)

# 安装
• 安装 .NET framework 4.8 运行库

• 下载并安装mpvnet_DW

• 运行mpvnet.exe

# 下载
见网页端右侧Releases或移动端下方Releases

# 鸣谢
感谢hooke007编写的mpv.net_CM，和各项说明；感谢cyl0编写的ModernX osc；感谢po5编写的thumbfast；感谢tsl0922编写的Implay，使thumbfast可以在mpvnet上使用