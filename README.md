# ADD-ARL-Finger
ARL灯塔添加指纹脚本支持两种模式
```
    usage:
        python3 ADD-ARL-Finger.py https://127.0.0.1:5003/ admin password old [file_path]   使用旧方式添加指纹
        指纹文件格式
        {
            "cms": "致远OA",
            "method": "keyword",
            "location": "rule: body",
            "keyword": [
                "/seeyon/USER-DATA/IMAGES/LOGIN/login.gif"
            ]
        }
        python3 ADD-ARL-Finger.py https://127.0.0.1:5003/ admin password new [file_path]   使用新方式上传指纹文件
        指纹文件格式为：
        - name: 致远OA
         rule: body="/seeyon/USER-DATA/IMAGES/LOGIN/login.gif"


```
现在支持新添加方式和旧添加方式都支持自定义指纹脚本路径，不添加路径的话，默认和脚本同目录的文件名为finger.json
