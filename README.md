# Biu-framework 🚀
[![GitHub issues](https://img.shields.io/github/issues/0xbug/Biu-framework.svg)](https://github.com/0xbug/Biu-framework/issues)
[![GitHub forks](https://img.shields.io/github/forks/0xbug/Biu-framework.svg)](https://github.com/0xbug/Biu-framework/network)
[![GitHub stars](https://img.shields.io/github/stars/0xbug/Biu-framework.svg)](https://github.com/0xbug/Biu-framework/stargazers)
[![Python 3.x](https://img.shields.io/badge/python-3.x-yellow.svg)](https://www.python.org/) 
[![GitHub license](https://img.shields.io/badge/license-GPLv3-blue.svg)](https://raw.githubusercontent.com/0xbug/Biu-framework/master/LICENSE)


中文版说明文档[点这里](https://github.com/0xbug/Biu-framework/blob/master/README_zh.md)

## Dependencies

Python3.x

## INSTALL

```
pip install -r requirements.txt
```

## Usage

```
usage: biu.py [-h] [-f F] [-d D] [-a A]

Biu~

optional arguments:
  -h, --help  show this help message and exit
  -f F        目标文件: 每行一个ip或域名
  -d D        目标: example.com或233.233.233.233
  -a A        ip范围: 233.233.233.233/24
```

## Plugin

### Just like this 🚀

```
{
    "name":"", // 名字
    "method": "GET", // 发包方式
    "port": [8080], // 可能的端口
    "suffix":"", // 目标的后缀
    "hits":[""] // 命中规则
}
```