### google.com官方包graphics

源地址：code.google.com/p/graphics-go/graphics

本地址的graphics包是直接从官网下载下来的，而且测试使用成功的。没有经过任何修改，请放心使用。

使用说明：复制 code.google.com  到 /go/src中，mod需要复制到


```
 cd ~/go/pkg/mod
 git clone git@github.com:zouhuigang/google-graphics.git
 mv google-graphics/* ./

golang程序：

    import (
	    "code.google.com/p/graphics-go/graphics"
    )
