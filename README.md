DEPRECATED
==========
This repository is retired. The two headers still in use, `SysMgrEvent.h`
and `SysMgrDeviceKeydefs.h`, now ship with
[luna-sysmgr-common](https://github.com/webOS-ports/luna-sysmgr-common)
and are installed under its include directory, covered by the
`LunaSysMgrCommon` pkg-config module. Nothing should depend on
`LunaSysMgrIpcMessages` anymore; former consumers (luna-sysmgr-common,
luna-displaymanager, luna-appmanager, sensorfw) have been untangled.

Summary
=======
This is the repository for public header files used by LunaSysMgrIpc, the webOS IPC library used by luna-sysmgr.

How to Build on Linux
=====================

This is built when you build luna-sysmgr:  
       openwebos/luna-sysmgr

# Copyright and License Information

All content, including all source code files and documentation files in this repository except otherwise noted are: 

 Copyright (c) 2010-2013 LG Electronics, Inc.

All content, including all source code files and documentation files in this repository except otherwise noted are:
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this content except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
