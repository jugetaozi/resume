# [resume](http://www.jugetaozi.com/resume/output/)

可以按照下列方法clone到本地  然后在模板的基础上面修修改改就可以做出一份漂亮的简历啦~~
----------
需要注意的是  需要全局安装fis3哦
```
npm install fis3 -g 
``` 
如果您喜欢这个模板简历,欢迎star或者fork ~~~~~
-----
| This is to support the H5 resume on PC and mobile.

## Ues

Download or Fork
```sh
$ npm install

and

$ npm install fis-parser-node-sass
```

Release to the default directory
```sh
$ fis3 release
```

 Start the server
```sh
$ fis3 server start
```
 Open your browser to http://127.0.0.1:8080/

 Automatically refresh
```sh
$ fis3 release -wL
```

Published to the specified directory
```sh
$ fis3 release -d [directory]
```

node 8.11.3
npm  5.6.0


npm未能加载Visual C++组件，解决办法win10

以管理员身份运行：Windows PowerShell

npm install --global --production windows-build-tools
npm install -g node-gyp
