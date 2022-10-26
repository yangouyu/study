#### conda使用手册
咱们使用conda时候都使用惯了，非常快就可以下载出来资源文件，直接食用就可以完成非常复杂的操作，不用其他软件就可以完成。

- 查看环境
  - conda info -e
- 创建环境  
因为不同的程序使用的Python版本是不同的。
  -  conda create -n name python=版本号
- 删除环境
  - conda remove -n 环境名 --all
- 切换环境
  - conda activate 环境名
- 安装包
  - conda install 包名
#### 其他
- conda config --add chanels 数据源地址 # 添加数据源
- conda info # 显示conda所有信息，包括数据源 -e 显示所有环境
- conda config --remove channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/ # 删除数据源
- conda --version # 检测当前conda版本
- conda update conda # 升级conda
- conda update # 更新所有包 加报名更新指定包
- conda deactivate. # 退出conda环境