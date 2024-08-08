# ADD-ARL-finger
ARL灯塔添加指纹脚本支持两种模式
```
    usage:
        python3 ARL-finger-ADD.py https://192.168.1.1:5003/ admin password    支持老形式如
       {
            "cms": "致远OA",
            "method": "keyword",
            "location": "rule: body",
            "keyword": [
                "/seeyon/USER-DATA/IMAGES/LOGIN/login.gif"
            ]
       }

        python3 script.py https://192.168.1.1:5003/ admin password [file_path]   支持ARL导出的指纹
```
不添加文件路径极为老模式添加，加上文件路径为ARL导出文件添加
格式为：
```
- name: 致远OA
  rule: body="/seeyon/USER-DATA/IMAGES/LOGIN/login.gif"
```
