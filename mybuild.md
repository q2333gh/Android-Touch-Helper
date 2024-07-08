VMware 中的 ubuntu desktop 的android studio 似乎不能直接跑qemu安卓虚拟机.
所以选择了windows平台编译.

发布release版本:


```ps1
# after build in android studio 项目根目录下:
Copy-Item -Path ".\app\release\TouchHelper_release.apk" -Destination ".\my_release\"
```