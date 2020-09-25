#### This project has migrated to [github.com/facebook/react](https://github.com/facebook/react)

The source code for the v3 of the extension can be found in the [`v3` branch](https://github.com/facebook/react-devtools/tree/v3).

To build the v3 browser extension from source:
```sh
git checkout v3

# Install dependencies and build the unpacked extension
yarn install
yarn build:extension

# Follow the on-screen instructions to complete installation
```

1.首先打开官网：https://github.com/facebook/react-devtools

2.本地打开git bash 然后复制上面的github下载链接
在git中输入：git clone https://github.com/facebook/react-devtools.git

3.克隆完成以后
cd react-devtools //切换到工程目录
cnpm i //安装依赖  有时候有安装依赖失败，这时候需要关闭360或者其他安全卫士

4.安装完成以后切换目录
cd shells/chrome //切换到chrome目录下

5.然后运行node build.js 当前目录下会生成build目录 这个build目录下的unpacked目录就是chrome中所需react-devtools的工具扩展程序包

chrome://extensions/ 进去扩展页面进行安装
