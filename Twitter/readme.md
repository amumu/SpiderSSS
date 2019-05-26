# Twitter 用户图片爬虫

    selenium
    urllib
    mysql


单个用户图片爬虫。
首先获取用户media下所有图片链接存入MySQL，然后下载张图片。

配置文件内容：config.py

```python
# 待爬取用户名
username = 'kaifulee'
# MySQL配置
host = '127.0.0.1'
user = 'root'
psd = '123456'
db = 'spiders'
c = 'utf8'
port = 3306
# 图片存储路径
path_img = './imgs/'
```