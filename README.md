# fis-mode-dev
项目运行时引入另一个公共仓库

### 安装

```
npm i fis-mode-dev -g
```

### 使用

在公共的仓库下使用
```
mvtool link
```


在运行的项目里面使用
```
mvtool sync
```

默认会移动到项目的根目录下， 有需求移动到项目的特定的目录下的可以使用

```
mvtool sync path
```

eg

```
mvtool sync src
```

### 注意：
公共仓库就会移动到运行的项目中, 会实时监听公共仓库的变化
