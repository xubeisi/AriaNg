https://xubeisi.github.io/a2

support: aria2c "https://google.com" --out "google.html" --header "User-Agent: www.google.com" --header "Cookie: XXXX"


- 原AriaNG https://github.com/mayswind/AriaNg
- yuchting https://github.com/yuchting/AriaNg/releases/ add this function -> https://github.com/mayswind/AriaNg/pull/601
- 感谢作者们 & p3TREX808080

## 编译
可以参考原 AriaNG 的编译，不过开发只能在 node v10 版本中编译，最新的 NodeJs 版本无法编译。

比如使用 v10 的nodejs.exe 编译：
```shell
/d/node-v10.24.1-win-x64/npm install
/d/node-v10.24.1-win-x64/node.exe ./node_modules/gulp/bin/gulp.js clean build
```

编译只有一个 index.html 文件：
```shell
/d/node-v10.24.1-win-x64/npm install
/d/node-v10.24.1-win-x64/node.exe ./node_modules/gulp/bin/gulp.js clean build-bundle
```

## 下载
https://github.com/yuchting/AriaNg/releases/ 





