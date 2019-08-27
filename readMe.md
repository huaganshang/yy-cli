### 说明
* 通过全局安装工具 yy-cli 工具来拉取最新的项目模板，可以是任何远程的GitHub、GitLab、Bitbucket 的仓库模板；
* 默认拉取的是一个基于 webpack4 + vue + vue-router + vuex + axios 进行快速开发的一个DEMO模板；

### 安装全局cli工具
```
npm i @yzone/yy-cli -g
```

### 查看版本
```
yy -V
```

### 查看帮助
```
yy -h
```

### 初始化项目
```
yy init <项目名称> [模板地址]

或者

yy create <项目名称> [模板地址]
```
* 参数：
    * 项目名称（必要参数）
        - 如果是已经存在的目录名，则会提示是否要覆盖安装；
        - 如果选择“否”，则退出安装；
        - 如果选择“是”，则会先删除存在的目录，再根据模板生成新的项目名；
    * 模板地址格式
        - GitHub: github:owner/name  或者 owner/name
        - GitLab: gitlab:owner/name
        - Bitbucket: bitbucket:owner/name
        - 如果不填写，默认从 "github:huaganshang/yzone-vue#master" 拉取；
