<h1 align="center"> Package Maker </h1>

<p align="center"> :package: A composer laravel package maker.</p>


# 安装方式


```shell
$ composer global require shineyork/laravel-package-maker:dev-master

或者

$ composer global require shineyork/laravel-package-maker

```

# 命令目录

```shell
 $ laravel-package-Maker
```

## 创建项目的命令

```
laravel-package-maker build [项目名 => name/com]
```

## 如下是实例

例如:
```shell
laravel-package-maker build foo/bar

Name of package (example: foo/bar): foo/bar
Namespace of package [Foo\Bar]:
Description of package:
Author name of package [shineyork]:
Author email of package [shineyork@sixstaredu.com]:
License of package [MIT]:
laravel service provider name : FooServiceProvider
Package foo/bar created in: ./foo/bar
```
