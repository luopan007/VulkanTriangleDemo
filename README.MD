# Vulkan triangle Demo

## 使用步骤：

### 安装Vulkan SDK

https://vulkan.lunarg.com/sdk/home

### 安装GLFW框架

https://www.glfw.org/download.html

### 安装GLM库

https://sourceforge.net/projects/ogl-math/

### 创建一个空的Windows Destop Wizard---Visual Studio IDE

### 配置头文件、库文件、连接器

#### 头文件路径配置--针对所有配配置生效
项目---属性---C/C++---常规---附件包含目录：写入Vuilkan/GLFW/GLM的头文件目录

#### 库文件路径配置--针对所有配配置生效
项目---属性---链接器---常规---附加库目录：写入Vulkan/GLFW的库文件目录

#### 库文件名字配置--针对所有配配置生效
项目---属性---链接器---输入---附加依赖项：写入Vulkan/GLFW的库文件名称

### 修改配置管理为x64，运行

