# Markup Starter Kit

[![Join the chat at https://gitter.im/lauraluo/markup-starter-kit](https://badges.gitter.im/lauraluo/markup-starter-kit.svg)](https://gitter.im/lauraluo/markup-starter-kit?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

- 使用 Jade
- 使用 Scss
- 使用 Gulp

# 安裝

```
npm install 
```

## 修複Ubuntu Gulp Watch 檔案權限

引用： http://stackoverflow.com/questions/16748737/grunt-watch-error-waiting-fatal-error-watch-enospc

```
echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p
```

## 檔案結構

待補

## Gulp Task

待補

## Gulp 一些相關工具的介紹————

### gulp-connect 

簡易伺服器
https://www.npmjs.com/package/gulp-connect