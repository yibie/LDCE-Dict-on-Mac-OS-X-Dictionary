## 致谢

感谢 [Archie-King](https://github.com/Archie-King/Longman-Dict-Apple-Dictionary) 和 [borghei](https://github.com/borghei/Dictionary-Development-Kit) 提供的资源。

## 使用方法

由于之前用 Archie-King 提供的方法，在编译词典文件时，总说缺少 DictionaryDevelopmentKit 相关文件。于是我又在 Github 找到 borghei 此前从 Apple Developer Downloads 备份的 DictionaryDevelopmentkit。

为方便后来者，我将它们都放在了一起。并将里面的 Make 文件里应当修改的路径都已经统一修改了。

1. 先到 Archie-King 的 [Repo](https://github.com/Archie-King/Longman-Dict-Apple-Dictionary) 把词典文件下载到本地；
2. 将眼前这个 Repo 下载到本地；
3. 将名为「DictionaryDevelopmentKit」的文件夹，复制到 /Applications/Utilities/ 之下；
4. 将「DictionaryDevelopmentKit」里的「project_templates」复制到 ~/Desktop/；
5. 在终端（iTerm 或者苹果自带的 Terminal），进入「Longman Dictionary of Contemporary English Online - En-En」文件夹，然后输入 make && make install；
6. 字典将自动安装好。

## Credits
Copyright © 1997-2018 Apple Inc. All rights reserved.
