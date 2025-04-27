node -v 查看node版本号
npm 包管理工具 -v查看npm版本
包管理工具 pnpm cnpm yarn ....

npm config ls 查看npm配置信息 -l查看全部配置

npm config set registry 镜像地址

npm config get registry 获取npm配置的注册地址

npm install(i) 根据包说明文件安装依赖
npm install(i) 包名@版本号 安装指定版本的包
    -g全局安装  -D(--dev)开发模式  -S(--save)本地安装
npm uninstall  包名@版本号 卸载指定版本的包

npm init 初始化包说明文件 (如果有package.json文件，则是前端的包)

Vue脚手架安装
Vue-cli (Vue2,Vue3)

npm i @vue/cli -g 全局安装Vue脚手架

Vite (Vue3)

npm create vite@latest 项目名 -- --template vue
npm run 脚本
        serve 启动vue项目
        build 打包
        test 测试

vue ui 图形化界面
