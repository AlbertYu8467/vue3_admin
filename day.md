# 规范
## 编程规范
## prettier
1. 安装vscode prettier插件
2. 根目录新建.prettierrc
3. 设置 - format on save
4. tabSize: 2

## git规范
- [约定式提交](https://www.conventionalcommits.org/zh-hans/v1.0.0/)
- [commitizen](https://github.com/commitizen/cz-cli)
1. `npm install -g commitizen`
2. `npm i cz-customizable -D`
3. package.json中添加以下命令
```
  "config": {
    "commitizen": {
      "path": "node_modules/cz-customizable"
    }
  }
```
4. 在根目录创建.cz-confing.js文件
5. 使用git cz 代替 git commit