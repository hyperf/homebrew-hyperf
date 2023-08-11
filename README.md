# Homebrew for Hyperf

## Install

```shell
brew tap hyperf/hyperf
```

### How to use autoconf

```shell
brew install hyperf/hyperf/autoconf@2.69
# brew unlink autoconf
brew link autoconf@2.69
```

### How to use php@8.1 with openssl v1.1

因为 brew 默认安装的 openssl 是 v3 版本，如果想使用 v1.1 版本，可以按照以下操作处理

```shell
brew uninstall php@8.1
brew install hyperf/hyperf/php@8.1
```
