# Ubuntu 16.04安装有道词典的方法

      今天在Ubuntu16.04下尝试安装有道词典
      官网下载：http://cidian.youdao.com/index-linux.html
      默认支持14.10及以上，14.04用户需要在安装前更新系统(update&dist-upgrade)


      这个版本1.1.0依赖性有问题，总是安装不上去，可以安装youdao-dict_1.0.2~ubuntu版本。参考：


      Ubuntu用户在安装前要更新系统，即update&dist-upgrade。
      下载地址：32/64bits
      http://codown.youdao.com/cidian/linux/youdao-dict_1.0.2~ubuntu_i386.deb
      http://codown.youdao.com/cidian/linux/youdao-dict_1.0.2~ubuntu_amd64.deb
      $ sudo dpkg -i youdao-dict_1.0.2~ubuntu_amd64.deb
      $ sudo apt-get install python3-pyqt5
      有些不能安装则$ sudo apt-get -f install
      $ sudo apt-get install tesseract-ocr
      $ sudo dpkg -i youdao-dict_1.0.2~ubuntu_amd64.deb


      尝试1.0.2 果断安装成功了。
