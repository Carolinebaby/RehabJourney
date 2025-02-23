# RehabJourney
康途同行，简易版远程康复平台

项目文档: [康途同行网站设计文档.md](https://github.com/Carolinebaby/RehabJourney/doc/康途同行网站设计文档.md)

项目结构：

```
Project
│
├─.venv
│
├─core  # 核心应用，model.py 定义所有应用使用的模型
│  │  admin.py
│  │  apps.py
│  │  consumers.py
│  │  form.py
│  │  models.py
│  │  routing.py
│  │  urls.py
│  │  views.py
│  │  __init__.py
│  │
│  ├─migrations
│  │
│  └─__pycache__
│
├─doctor  # 医生应用
│  │  apps.py
│  │  urls.py
│  │  views.py
│  │  __init__.py
│  │
│  ├─migrations
│  │
│  └─__pycache__
│
├─media  # 用户上传文件存储地址
│  ├─avatar
│  └─chat_files
│ 
│
├─patient  # 患者应用
│  │  apps.py
│  │  urls.py
│  │  views.py
│  │  __init__.py
│  │
│  ├─migrations
│  │  │  __init__.py
│  │  │
│  │  └─__pycache__
│  │          __init__.cpython-311.pyc
│  │
│  └─__pycache__
│
├─Project  # 全局配置目录
│  │  asgi.py
│  │  settings.py
│  │  urls.py
│  │  wsgi.py
│  │  __init__.py
│  │
│  └─__pycache__
│
├─static  # 静态资源
│
├─manage.py
│
│ # tailwind css 组件的相关配置文件
├─node_modules
├─package.json
├─package-lock.json
├─postcss.config.js
├─tailwind.config.js
│
└─templates  # 模板
    │  core_base.html
    │  doctor_base.html
    │  patient_base.html
    │  patient_chat_base.html
    │
    ├─core
    │      about.html
    │      index.html
    │      login.html
    │      signup.html
    │
    ├─doctor
    │      chat.html
    │      index.html
    │      modify_info.html
    │      patient_health_plan.html
    │      patient_info.html
    │      patient_manage.html
    │      personal_info.html
    │
    └─patient
            chat.html
            contact.html
            health_data.html
            health_plan.html
            index.html
            medication_record.html
            modify_info.html
            personal_info.html
```
