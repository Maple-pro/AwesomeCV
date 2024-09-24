# Resume and CV

> 使用 [Awesome-CV](https://github.com/posquit0/Awesome-CV) 模板

## 1 概览

| 文件                     | 用途                                |
| ------------------------ | ----------------------------------- |
| resume-maples-cn-multi   | 中文 resume，体制内简历             |
| resume-maples-cn-onepage | 中文 resume，大厂简历               |
| resume                   | 英文 resume 模板（未使用）          |
| ~~resume-maples-cn~~     | ~~中文 resume，大厂简历（已废弃）~~ |
| CV                       | 英文 CV 模板                        |
| coverletter              | 英文 coverletter 模板               |

## 2 字体

- 中文字体采用 Source Han Sans SC 
- 英文字体采用 Source Sans Pro

### 2.1 中文字体安装

Arch Linux：安装 [adobe-source-han-fonts](https://aur.archlinux.org/packages/adobe-source-han-fonts) 字体

Windows：使用 **管理员权限** 安装 `fonts-cn` 目录下的字体

查看 Latex 可检索到的字体：

```bash
# 查看所有字体
fc-list

# 查看中文字体
fc-list :lang=zh-cn

# 查看字体是否包含所需字体
fc-list | grep -i "Source Han Sans SC"
```

### 2.2 中文字体使用

```tex
\documentclass[11pt, a4paper]{awesome-cv-cn}
\usepackage[UTF8]{ctex}
\setCJKmainfont{Source Han Sans SC}
```

### 2.3 fontawesome

目前使用版本为 4.4.0，可查看 [Icon List](https://fontawesome.com/v4/icons/)
