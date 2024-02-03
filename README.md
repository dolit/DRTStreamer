 English | [简体中文](./README_cn.md)



# dolit real-time streamer

Dolit Real-time Streamer can stream any application to a web page, enabling real-time use on lightweight devices.

## Project Scenarios

Widely applicable to the web presentation of 3D content (such as digital twins, smart cities, and three-dimensional visualization), remote desktop, remote control, cloud VR, real-time cloud rendering, cloud desktops, cloud applications, and more, the Dolit Real-time Streamer contributes to low-latency, high-quality, immersive interactive experiences for large software and applications.

Additionally, an SDK is provided for integration into other software systems, offering foundational technical support for remote operations and maintenance, enterprise-level remote control, and single-application streaming.

## Project Features

- Real-time streaming of an entire computer desktop or any application to a web page, with no plugins required for the web client, enabling instant use.
- Proprietary ultra-low latency transmission technology, achieving sub-5ms round-trip delays in local networks (from command issuance to screen capture, real-time video stream encoding, network transmission, and decoding display).
- Supports multi-process containerized isolation on a single server for multiple concurrent streams, ensuring processes do not interfere with each other.
- Off-screen rendering for 3D applications built with engines like Unreal, Unity, and WebGL, reducing server load by not displaying content screens.
- Compatible with a wide range of software applications, including UG, AutoCAD, and drawing boards.
- Capable of streaming the entire computer desktop for remote control or remote desktop applications.
- Supports cluster deployment and load balancing, automatically selecting the optimal route for access.
- Multi-GPU support on a single machine, automatically balancing the load across graphics cards.
- Accessible and controllable from computers, smartphones, tablets, VR/AR devices, set-top boxes, and conference screens, among other light terminal equipment.
- Compatible with a variety of browsers, including Chrome, Safari, and others in Chrome mode, such as 360 Speed Browser, Sogou Browser, QQ Browser, Huawei Browser, as well as WeChat’s built-in browser and mini-programs.
- In addition to web clients, Windows, Android, and iOS clients are available for even lower latency experiences.
- Custom resolution support to adapt the display to different terminal resolutions, with options for original size, fit-to-width height, and full screen.
- Configurable video encoding, including bitrate and other parameters, with support for different resolutions such as 720P, 1080P, 2K, 4K, 8K. Front-end adaptive bitrate and bandwidth.
- 8K resolution support and H.265 decoding for devices capable, offering clarity at 8K@60hz on standard Chrome browsers.
- Supports Windows 10, Windows 11, Windows Server 2016, 2019, 2022, and various Linux systems like Ubuntu, Centos, Debian, and RedHat.
- Compatible with China’s domestic Trustworthy Computing systems, including UOS, Kylin OS, EulerOS, Zhongke Fangde, Deepin, and others.
- Compatibility with some data center GPUs/Tesla, Quadro professional graphics cards, and consumer-level RTX and GeForce series.
- Multi-user simultaneous viewing support, with primary control and spectator mode, including request controls for observers.
- Application distribution based on Dolit P2P, supporting pause and resume, centralized deployment, and uniform distribution.
- Second development interfaces/APIs/SDKs are provided for easy secondary development and business integration.
- Communication plugins can be integrated during UE/Unity development for bidirectional custom message communication with web clients.
- A visual web-based management platform is available, including machine management, application management, and stream routing management.
- Real-time monitoring of machine load with configurable load threshold parameters to prevent overload and ensure an optimal experience.
- Application reports and user usage statistics are provided, including usage duration, number of uses, peak online user counts, yesterday’s visitor count, and current online users, with customizable query times and criteria.
- Audio and video call mechanisms are supported, enabling multi-person calls during control operations.
- Sharing of operator screens and cameras to the streamed content is supported, facilitating control and communication.
- Bird’s-eye view mode: For large-screen applications, dynamic partial screen capture is supported based on front-end display needs, with a slider to select specific content areas, reducing bandwidth consumption and enhancing image quality.

## Overview of System Architecture

![scenario](https://raw.githubusercontent.com/dolit/DRTStreamer/master/www/scenario.jpg)



## Contact Information

Email：market@dolit.cn 

WebSite：https://www.dolit.cloud 

[Please visit this link for more...](https://dolit.cloud/)

