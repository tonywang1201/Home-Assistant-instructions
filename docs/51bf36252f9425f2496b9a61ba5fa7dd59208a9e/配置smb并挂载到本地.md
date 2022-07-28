# 配置samba share

## 1. 进入加载项商店安装插件

- 加载项商店内搜索**samba share**
  
  ![](https://mypic-1303950876.cos.ap-shanghai.myqcloud.com/img/加载项商店.png)

- 选择插件点击**安装**

## 2. 配置插件

- 选择**配置**选项卡

- 在**username**处填写**用户名**

- 在**password**处填写**密码**
  
  ![](https://mypic-1303950876.cos.ap-shanghai.myqcloud.com/img/配置smb.png)

## 3. 连接到homeassistant

- 进入Windows**文件管理器**或者Mac**访达**

- Windows顶部**计算机**-**映射网络驱动器**；Mac在**前往**内选择**连接服务器**

- 如图所示填入地址：
  
  Windows: `\\homeassistant.local\local`
  
  Mac: smb://homeassistant
  
  ![](https://mypic-1303950876.cos.ap-shanghai.myqcloud.com/img/windows添加smb.PNG)
  
  ![](https://mypic-1303950876.cos.ap-shanghai.myqcloud.com/img/mac添加smb.png)

- 连接到服务器后即可将服务器挂载到本地
