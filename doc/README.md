
## 使用方法
1. 下载源码 git clone xxx
2. 根目录下执行命令 npm install
3. 调试时，使用 npm run dev，
4. 编译时，请使用 npm run build, 生成的文件在 app/vueDist目录下。
5. 打包时，进入app目录下,请使用 electron-builder ,生成build文件夹，点击.exe文件运行

##快速删除node_modules
全局安装rimraf：
npm install rimraf -g
到你的项目根目录下（即有node_modules的目录），执行命令：
rimraf node_modules