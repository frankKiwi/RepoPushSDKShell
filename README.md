1、CreateShellScript：快捷的可执行文件shell脚本，作用是快速创建shell脚本的可执行文件，创建好后已在脚本内容输入了 #!/bin/bash 解释器内容；

2、CreateCocoapodsRepoProjectScript：快速创建基于cocoapods的私有库/公有库脚本，作用是快速创建cocoapods的私有库/公有库的工程脚本，创建完后自动将远端仓库里的另一个自动化推送脚本下载至本地的工程的root目录下；

3、RepoPushShellScript：基于cocoapods的私有库/公有库工程的自动化push repo脚本，作用是自动化实现cocoapods的私有库/公有库工程的整个push repo流程，并对私有库引用私有库，公有库引用私有库的情况做了支出；

4、CreateReadmeScript：简单小脚本，用于快速创建README.md文件，文件的内容如果需要换行的请用#隔开

5、ClippingImageShellScript：简单的自动化制作整套icon的脚本，用于动态裁切出一套适用于竖屏的ios-icon，使用时需要一张未做基本裁切的icon图标，最好是1024x1024尺寸的

6、LogImageInfosShellScript：简单的png格式图片、图标信息打印脚本，用于快速打印出当前脚本路径下的所有png格式图片的信息

7、ModiffitedImageNamesShellScript：批量修改图标名称，用于处理@1x、@2x、@3x图标的批量修改，面向格式为png格式

8、FlutterStartShellScript：启动flutter工程的自动脚本，用于快速启动flutter工程，并且允许设置release或者debug模式，使用时需要将脚本放置在flutter工程的root目录下

9、ClearFlutterLocationCacheShellScript：清除flutter工程中的lockfile缓存文件，用于处理Waiting for another flutter command to release the startup lock...问题
