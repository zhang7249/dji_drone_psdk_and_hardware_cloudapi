# dji_drone_psdk_and_hardware
Based on DJI drones, the PSDK provides a complete set of solutions. 


#### 我们是一家专门基于无人机psdk和osdk进行开发应用的团队，坐标在中国，目前生产出了可以替代官方的硬件盒子（以下简称盒子），使用了nx板+5g芯片，良好的工程设计，保证了硬件的质量稳定，性能强劲。
### 盒子是基于nx板，所有具有一定的算力，可以运行一些轻模型。
#### 盒子支持挂载在大疆无人机m300,m30t,m350等主流行业级无人机上。
#### 我们有一整套的无人机解决方案，从设备端到服务端，设备端即硬件盒子加上psdk代码，服务端以jar包的形式提供，接口清晰明了，使得用户可以快速的开展起业务，并不需要关注实现过程，简单20分钟的开发，就可以通过一条简单的http请求使飞机起飞。
#### 盒子内置psdk代码实现了图传、手动飞行、云台控制、航线控制、飞行数据回传等等基础功能，使用私有协议与后端进行通信，经过长期测试，延时低（指令毫秒级，图传受网络影响波动较大，我们会根据网络速度实时的自适应推流分辨率和码率，以保证延迟小于500ms，稳定200ms），稳定性好。
#### 我们也有开发基于msdk的app，和psdk使用的同一套协议，支持基础飞控的所有功能。
#### 并且我们也基于大疆上云api开发了机库的飞控系统，基本支持大疆开放的所有功能。
#### 欢迎有兴趣的朋友联系交流，后面附上我们的产品外形图。
#### 欢迎发邮件交流：zhangxiaolan940601@gmail.com


#### Here is a translated version of the document generated based on ChatGPT. If there are any ambiguities, feel free to email us for further discussion: zhangxiaolan940601@gmail.com

#### We are a team specializing in the development and application of DJI drone PSDK and OSDK. Our team is based in China, and we have successfully produced a hardware device (referred to as "box" below) as a replacement for the official one. The box consists of an NX board and a 5G chip, featuring excellent engineering design to ensure stable hardware quality and powerful performance.
#### The box is based on the NX board and has a certain computing power, capable of running some lightweight models.
#### The box is compatible with DJI drones such as M300, M30t, M350, which are widely used in various industries.
#### We offer a complete drone solution, from the device side to the server side. On the device side, the hardware box is combined with PSDK code, while the server side provides the functionality in the form of a jar package. The interface is clear and concise, allowing users to quickly develop their own businesses without worrying about the implementation details. With just a simple HTTP request, the aircraft can take off within 20 minutes of easy development.
#### The built-in PSDK code in the box provides basic features such as image transmission, manual flight, gimbal control, flight route control, flight data feedback, and more. It communicates with the backend using a proprietary protocol based on Java-Netty. After extensive testing, it has low latency (instruction-level in milliseconds, while image transmission can be affected by network fluctuations). We dynamically adjust the streaming resolution and bitrate based on network speed to keep the delay below 500ms and maintain stability at around 200ms.
We have also developed an app based on MSDk, using the same protocol as PSDK, which supports all the basic functionalities of flight control.
#### Additionally, we have developed a flight control system called "Airframe Library" based on DJI's cloud API, which supports almost all the functions provided by DJI.
#### We welcome anyone interested to contact us for further discussion. Attached below is the image of our product's appearance.

#### Feel free to email us for further discussion at zhangxiaolan940601@gmail.com.


![image](https://github.com/zhang7249/dji_drone_psdk_and_hardware/assets/23712584/ef4731e8-b919-4d8d-82c6-9460c5cf85e7)

![image](https://github.com/zhang7249/dji_drone_psdk_and_hardware/assets/23712584/da895db5-72d8-4c0a-8ef2-fd41fe7a5b5f)




