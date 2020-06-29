# TweetApprover
## 下载到本地
```
git clone https://github.com/OoGod/myBlog.git
```

## 进入myBlog目录，运行下列命令
```
python install -r requirements.txt
manage.py runserver
```

## 注: 运行manage.py runserver时需注释掉settings中下列3行代码
```
django_heroku.settings(locals())
import dj_database_url
DATABASES['default']=dj_database_url.config(conn_max_age=600,ssl_require=True)
```

## 进入后台管理界面
```
manage.py createsuperuser # 创建超用户
# 输入127.0.0.1：8000/admin
```
