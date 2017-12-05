
1，安装node.js（官网：https://nodejs.org/zh-cn/）

// 查看node.js的版本

node -v 

// 查看npm的版本

npm -v

// 设置代理

npm install -g cnpm --registry=https://registry.npm.taobao.org

2，安装webpack（打包工具）

// 命令

npm install webpack -g

// 查看webpack的版本

webpack -v

3，安装vue cli（vue的命令行工具）

// 命令

npm install vue-cli -g

// 查看vue cli版本

vue --version

4，新建项目

// 命令

vue init webpack 项目名

5，安装项目依赖（进入项目所在目录进行安装）

// 命令

npm install

// 运行

npm run dev

// 打包（需要注意修改路径，config->index.js中assetsPublicPath的值修改为 ./）

npm run build
