# 链接转二维码·批量处理小工具

## 这能做什么
- [x] Url2QRCode：将链接批量处理为二维码 并保存图片到本地
- [x] Docx：将二维码及标题信息，以docx格式整理为文档
- [ ] Upload：将图文上传至后台管理系统 (❗暂未完成)

## 使用方式
1. 在info.txt中逐行写入要转码的`链接URL`和`链接名称`(可不填 会自动捕获页面标题；若填写 两者之间用`一个空格`隔开
2. 运行主程序：`python app.py` (若无依赖包，请先通过pip下载)
3. 该工具会在项目根目录下生成一个`qrcode`文件夹，一个`qrcode****.docx`文档。
    - qrcode内为链接转成的二维码
    - docx文档是二维码及标题信息

## 服务人群

该工具主要面向北京工业大学就业中心新媒体工作室的老师同学们，便于收集就业信息后，将信息自动整理并上传至就业中心后台。