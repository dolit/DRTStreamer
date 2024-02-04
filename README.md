 English | [简体中文](./README_cn.md)



# dolit real-time streamer

Dolit Real-Time Streamer can stream any application/desktop to a web page, enabling instant use on various lightweight devices through browser or a light client, with low-latency remote interaction with applications/desktop.

![scenario](https://raw.githubusercontent.com/dolit/DRTStreamer/master/www/scenario.jpg)

## Project Scenarios

Widely applicable to the web presentation of 3D content such as digital twins, smart cities, and three-dimensional visualization, remote desktop, remote control, cloud VR, real-time cloud rendering, cloud desktops, cloud applications, and more, the Dolit Real-Time Streamer contributes to low-latency, high-quality, immersive interactive experiences for large software and applications.

Additionally, an SDK is provided for integration into other software systems, offering foundational technical support for remote operations and maintenance, enterprise-level remote control, and single-application streaming.

## Features

- Real-time streaming of an entire computer desktop or any application to a web page, with no plugins required for the web client, enabling instant use.
- Proprietary ultra-low latency transmission technology, achieving sub-5ms round-trip delays in local networks (from command issuance to screen capture, to real-time video stream encoding, to network transmission, and to decoding display).
- CELL Isolation: Supports multi-process containerized isolation on a single server for multiple concurrent streams, ensuring processes do not interfere with each other.
- Off-screen rendering for 3D applications built with engines like Unreal, Unity, and WebGL, No content screen on the server to reduce the load.
- Compatible with a wide range of software applications, including UG, AutoCAD,  and drawing boards, among many others.
- Capable of streaming the entire computer desktop for remote control or remote desktop applications.
- Supports cluster deployment and load balancing, It can automatically select the optimal route for access.
- ·Multi-GPU support on a stand-alone computer, automatically balancing the load across graphics cards.
- Accessible and controllable from computers, smartphones, tablets, VR/AR devices, set-top boxes, and conference screens, among other light terminal equipment.
- Compatible with a variety of browsers, including Chrome, Safari, 360 Speed Browser in Chrome mode, Sogou Browser in Chrome mode, QQ Browser, Huawei Browser, as well as WeChat’s built-in browser and mini-programs.
- In addition to web pages, Windows, Android, and iOS clients are available for lower latency experiences. 
- Custom resolution support to adapt the display to different terminal resolutions, with options for original size, width, height, and full screen.
- Configurable video encoding, including bitrate and other parameters, with support for different resolutions such as 720P, 1080P, 2K, 4K, 8K, and front-end adaptive bitrate and bandwidth.
- Devices supporting H.265 decoding can playback in H.265 mode, offering clarity at 8K@60hz on standard Chrome browsers.
- Supports Windows 10, Windows 11, Windows Server 2016, 2019, 2022, etc. and various Linux systems like Ubuntu, Centos, Debian, and RedHat.
- Compatible with China’s domestic systems, including UOS, Kylin OS, EulerOS, Delix, Deepin, and others.
- Compatibility with some data center GPUs/Tesla, Quadro professional graphics cards, and consumer-level RTX and GeForce series.
- Supports multi-user simultaneous viewing, with primary control and spectator mode, including request controls for observers.
- Supports application distribution based on Dolit P2P, stop-and-go, centralized deployment, and uniform distribution.
- Second development interfaces/API/SDKs are provided for easy secondary development and integration.
- Communication plugins can be integrated during UE/Unity development for bidirectional custom message communication with web clients.
- A visual web-based management platform is available, including device management, application management, and stream routing management.
- Real-time monitoring of machine load with configurable load threshold parameters to prevent overload and ensure an optimal experience.
- Application reports and user usage statistics are provided, including usage duration, number of uses, peak online presence, yesterday’s visitors, and current online users, with customizable query times and criteria.
- Support audio and video call mechanisms, enabling multi-person calls during operations.
- Sharing of operator screens and cameras to the streamed content is supported, facilitating control and communication.
- Bird’s-eye view mode: For large-screen applications, dynamic partial screen capture is supported based on front-end display needs, with a slider to select content areas, reducing bandwidth consumption and enhancing image quality.

##  Architecture

![architecture](https://raw.githubusercontent.com/dolit/DRTStreamer/master/www/architecture.png)



## Contact Information

Email：market@dolit.cn 

WebSite：http://www.dolit.cloud 

[Please visit this link for more...](http://www.dolit.cloud/)

