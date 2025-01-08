Ubuntu GUI
===

Ubuntuのデスクトップ環境をCodespacesで構築します。

おおよそ4分くらいで構築できます。


## VNCサーバの起動

```bash
USER=root vncserver :1 -geometry 800x600 -depth 24
websockify -D --web=/usr/share/novnc/ 80 localhost:5901
```
