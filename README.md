# portsip-softphone-windows

The PortSIP Softphone for Windows is a free SIP softphone which built base on PortSIP UC SDK(https://www.portsip.com/portsip-uc-sdk), it supports below features:
Audio call
Video call
IM
Presence
Send file
Send picture
Send voice and video message
Video conference


## Table of Contents

- [Getting Started](#getting-started)   
  - [Prerequisites](#prerequisites)   
- [Installing](#installing)   
  - [Structure of portsip-softphone-windows](#structure of portsip-softphone-windows)    
- [SDK Reference](#sdk-reference)   
- [Contributing](#contributing)
  

## Getting Started

The project needs to be based on UC-SDK/Portsip PBX server /vsiual studio 2017

### Prerequisites
The project provides all the libraries needed for compilation, but if you need to edit the UI interface, you may need to use IUI tools.

For more information about IUI tools, please refer to Readme.txt in the [IUI] directory.

## Installing

1. Directly use source code internal projects and related components
2. Use CMAKE to generate visual studio project

### Structure of portsip-softphone-windows

```
├── [cmake]
	├── [msvcpch.cmake] <-- cmake pre process
	├── [PostBuild.cmd] <-- a bat file about built complete
├── [IUI]  <-- a UI library that requires a separate authorization
├── [jsoncpp]  <-- json library src files
├── [Keeper]   <-- a small client to startup  portsip-softphone
├── [PortSIPUC]   <--  portsip-softphone core code 
├── [sqlite3]   <--  db src files 
├── CMakeLists.txt <-- cmake project src file
├── LICENSE
└── readme.txt / readme.md
```


## SDK Reference

1.If you would like to get a local copy of the UC-SDK reference, you may [download it here](https://github.com/portsip/portsip-uc-sdk-sample-win.git).

2.If you would like to get more info about REST API,you may visit [Cloud REST APIs](http://www.portsip.cn/pbx-rest-api/v12.2/overview.html).


## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

Copyright ©2020 portsip, Inc. All rights reserved.
