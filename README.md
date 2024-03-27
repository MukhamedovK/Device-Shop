# DeviceShop-Ecommerce

COLLABORATORS
https://github.com/Winchestor2001
https://github.com/azizxojaev

CELERY RUN
```bash
celery -A core worker -l INFO -P eventlet
```

CELERY BEAT RUN
```bash
celery -A core beat -l INFO
```
