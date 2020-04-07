# 打卡宝
每天打开要烦死了，所以用selenium写了个NEU健康打卡自动版
# 如何使用？
## 1. 安装selenium
可以参考[安装selenium](http://www.testclass.net/selenium_python/install-selenium)教程
## 2.代码修改
只需要把下面的账号和密码改成自己的就可以进行自动打卡
```python
user=driver.find_element_by_xpath(r'//input[@type="text"]')
user.clear()
user.send_keys("账号")#账号
user.click()
password = driver.find_element_by_xpath(r'//input[@type="password"]')
password.clear()
password.send_keys("密码")#密码
password.click()
```
## 3. 利用.pyw
如果你是window系统，可以将.py文件的后缀改为.pyw。.pyw可以看做一个.exe文件，这样你可以直接点击.pyw文件来运行打卡程序。
