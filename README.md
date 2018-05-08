# 番号磁链获取器
获取Javbus上的数据并保存到MongoDB数据库

### 依赖库
- python3
- requests
- BeautifulSoup4
- progress
- re
- math
- random
- pymongo

### 使用方法

1. `git clone https://github.com/MyFaith/JavbusGetter.git`
2. `apt-get install python3-pip`
3. `pip3 install BeautifulSoup4 requests pymongo`
4. 修改javbus.py中的服务器配置 `mongo = MongoClient(host='192.168.199.217')`
5. `python javbus.py -page 10 -thread 4 -type 1` (page 页数 thread 启用线程数 type 1有码 2无码)

### 运行结果
![1.png](https://ooo.0o0.ooo/2017/03/04/58ba86e297b31.png)
