# iOS_CodeSnippets

用于 Xcode日常开发 的 iOS 通用代码片段集

## 使用方式

Xcode 的 Code Snippets 文件存放于 `~/Library/Developer/Xcode/UserData/CodeSnippets` 目录，只要直接把 `*.codesnippets` 文件放到这个目录下（若没有则自己创建），重启 Xcode 即可生效。

为了方便更新，建议直接将 iOS CodeSnippets clone 到这个目录内（注意，不是在 CodeSnippets 里创建一个目录，这里不支持子目录）：

```bash
cd ~/Library/Developer/Xcode/UserData/CodeSnippets
git clone https://github.com/cqzhong/iOS_CodeSnippets.git ./
```

注意，Xcode 对每一段 Code Snippet 都有规定适用的语言（Objective-C、Objective-C++、Swift、...）和作用域（如 Class 的 Interface 定义内、Class 的 Implementation 内、方法体内、...），所以测试某段 Code Snippet 不生效时请注意你当前是否处于不匹配的位置。

### 参考链接 [QMUI_iOS_CodeSnippets](https://github.com/QMUI/QMUI_iOS_CodeSnippets)
