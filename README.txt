光纤激光切割设备销售作战台（佛山·东莞）— 离线网页应用（PWA）

文件：index.html（全部界面与逻辑，无外部依赖）、manifest.json、sw.js（离线缓存）、图标 PNG。
本地试用：在本文件夹运行  python3 -m http.server 8080 ，手机与电脑同一 WiFi 时访问 http://电脑IP:8080/
（注：离线缓存/添加到主屏幕需要 https 或 localhost；直接双击 index.html 也能用，但没有离线缓存）
数据只保存在当前浏览器本地（localStorage），请在「更多 → 数据与备份」定期“复制备份文本”。
本应用不会联系任何客户，复制按钮只复制文字到剪贴板。
