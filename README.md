# bundler
自制打包器，通过入口文件完成依赖收集。

## 原理
使用babylon将入口文件转化文AST，通过分析ImportDeclaration，实习递归依赖收集。

![](./demo.png)

## License
[MIT](./LICENSE)

Copyright (c) 2019-present CalvinLee
