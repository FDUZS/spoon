[![Build status](https://ci.appveyor.com/api/projects/status/6f2p9phb7jwsy0jd/branch/main?svg=true)](https://ci.appveyor.com/project/FDUZS/spoon/branch/main)
[![GitHub license](https://img.shields.io/github/license/FDUZS/spoon?style=flat-square)](https://github.com/FDUZS/spoon/blob/master/LICENSE)
![GitHub repo size](https://img.shields.io/github/repo-size/FDUZS/spoon?style=flat-square)

# 🥄 Spoon bucket for Scoop

A [Scoop](https://github.com/lukesampson/scoop) [bucket](https://github.com/lukesampson/scoop/wiki/Buckets) for personal use based on this [template](https://github.com/Ash258/GenericBucket) and [dorado](https://github.com/chawyehsu/dorado) bucket.

More about Scoop:

- [Scoop 不完全上手指南](https://www.iamzs.top/archives/scoop-guidebook.html)
- [「一行代码」搞定软件安装卸载，用 Scoop 管理你的 Windows 软件](https://sspai.com/post/52496)
- [再谈谈 Scoop 这个 Windows 下的软件包管理器](https://www.h404bi.com/blog/2018/05/talk-about-scoop-the-package-manager-for-windows-again)

## Bucket Filter

~~Only Apps *Not* available in `scoop bucket known` buckets.~~

## Usage

```powershell
scoop bucket add spoon https://github.com/FDUZS/spoon.git
scoop install spoon/<app>
```

## Suggestion

Forget about maintaining your own bucket, use the `extras` bucket instead and contribute to it.

Moreover, [winget](https://winget.run/) may be a better option at the time of writing.
