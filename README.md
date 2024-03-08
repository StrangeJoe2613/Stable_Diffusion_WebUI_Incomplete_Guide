<p align="center">
<img src="https://cdn-uploads.huggingface.co/production/uploads/65ea1c7c88cb0da4669a18bf/fbz7IrfN9l7O92urnepX5.jpeg" alt="Image" style="display: block; margin: auto;" />
</p>

<h3 align="center">✨✨✨ Stable Diffusion WebUI - 使用不完全指南 ! ✨✨✨</h3>

<p align="center">本指南只是用来记录自己安装使用Stable Diffusion WebUI的过程<br>
以及学习Martdown和Html的语法与实践</p>

<div align="center">
  
| [简体中文](https://github.com/StrangeJoe2613/Stable_Diffusion_WebUI_Incomplete_Guide) | [英文](https://github.com/StrangeJoe2613/Stable_Diffusion_WebUI_Incomplete_Guide/blob/main/README.en_US.md) | [变更日志]() |
</div>

<p align="center">
Tips:
<a>[🔗链接]</a> <a>[⬇️下载]</a> <a>[📦程序]</a> <a>[📚压缩包]</a> <a>[📁文件夹]</a> <a>[💡提示]</a> <a>[✅已选择]</a> <a>[🔳未选择]</a>
</p>

![TtH4XnIe27grMD1DT-aYf](https://github.com/StrangeJoe2613/Stable_Diffusion_WebUI_Incomplete_Guide/assets/107075016/869afb2f-8cbb-4a32-b8fc-be449aa50225)

---

#### ⭐什么是Stable Diffusion WebUI ❓
 - Stable Diffusion WebUI是 <a href="https://github.com/AUTOMATIC1111/stable-diffusion-webui" style="background-color: #3498db; color: #ffffff; padding: 2px 6px; text-decoration: none; border-radius: 4px;">🔗AUTOMATIC1111</a> 根据Stable Diffusion制作的网页图形界面，其易用性大大的降低了Stable Diffusion的使用门槛。

#### ⭐什么是Stable Diffusion WebUI 绘世启动器 ❓
 - 指南使用的Stable Diffusion WebUI启动器是B站大佬(BiliBili) <a href="https://space.bilibili.com/12566101" style="background-color: #3498db; color: #ffffff; padding: 2px 6px; text-decoration: none; border-radius: 4px;">🔗秋叶aaaki</a> 的作品，其启动器整合了一键启动、配置选项、疑难解答、模型扩展管理等等诸多功能。

   ![image](https://github.com/StrangeJoe2613/Stable_Diffusion_WebUI_Incomplete_Guide/assets/107075016/7312e3e9-84ad-4aa5-8eac-e31bb088d0f8)

#### ⭐这不是一个整合包 ❌
 - 这个指南需要自行安装模型、Lora、扩展等。

---


### 📦开始

#### ⭐部署绘世启动器

 - 1、点击<a href="https://github.com/StrangeJoe2613/Stable_Diffusion_WebUI_Incomplete_Guide/raw/main/%E7%BB%98%E4%B8%96%E5%90%AF%E5%8A%A8%E5%99%A8@%E7%A7%8B%E8%91%89aaaki.rar" style="background-color: #2CDC2C; color: #ffffff; padding: 2px 6px; text-decoration: none; border-radius: 4px;">⬇️Download</a> 下载 绘世启动器。 

 - 2、下载后解压压缩文件 `📚绘世启动器@秋葉aaaki.rar` 。
 
 - 3、把解压得到的安装包 `📦绘世启动器@秋葉aaaki.exe` 放到你希望安装WebUI的地方。
   
     - 比如把 `📦绘世启动器@秋葉aaaki.exe` 放到D盘新建的 `📁WebUi` 文件夹中。( 路径为 D:/WebUI/绘世启动器@秋葉aaaki.exe )
       
     - (❗❗❗注意：打开启动器后，文件会自动下载到根目录，请务必不要放到盘符的根目录或桌面打开它，请根据你的需求，放到任意盘符下的 文件夹(起什么名字都行) 中。
       
 - 4、打开文件夹中的 `📦绘世启动器@秋葉aaaki.exe` 后，会出现 `💡正在下载更新文件，这可能需要一会儿时间。` ，这是它在安装启动器必须的文件，等待就行了。
 
 - 5、安装过程中会出现 `💡找不到内核` 的提示，点确定继续下一步。
 
 - 6、安装过程中会出现 `💡启动器检测的您的文件夹中缺少必要文件，是否尝试下载内核。` 的提示，点确定继续下一步。
 
 - 7、安装过程中会出现 `💡内核安装` 的界面。(默认点安装即可，但防止不小心点错，下面的默认选项可参考。)
   
     - 选择内核分支：AUTOMATIC1111/stable-diffusion-webui - 主线
       
     - ✅安装原生环境组件
       
       - ✅安装 Python
         
       - ✅安装 Git
         
       - ✅安装 Visual C++ 运行库
         
     - ✅安装 PyTorch
       
       - ✅选择版本：Torch 2.2.0(CUDA 12.1) + xFormers 0.0.24
         
     - ✅使用国内镜像
       
 - 8、安装过程中会出现 `💡你确定要开始安装吗？` 的提示，点是继续下一步。
 
 - 9、安装过程中会出现 `💡正在配置组件` 的cmd窗口，不用管，等待它自动完成，完成后它会自动关闭窗口。

#### ⭐运行WebUI

 - 1、再次打开 `绘世启动器@秋葉aaaki` ，点击左边菜单栏中的 [一键启动] 里右下角的 [一键启动] 。

 - 2、等待一会儿后，浏览器中出现网址为 `http://127.0.0.1:7860/` 的网站，这就是WebUI。

 - 3、WebUI的具体使用教程，需要自行去查询。

#### ⭐安装扩展

 - 1、

#### ⭐安装模型

 - 1、

#### ⭐关键词

 - 1、

#### ⭐尝试生成一张图

 - 1、

#### ⭐使用Lora

 - 1、

#### ⭐使用超网格

 - 1、

#### ⭐尝试制作一个视频

 - 1、

#### ⭐训练Lora

 - 1、

#### ⭐
