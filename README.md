# Model

class Post(models.Model):
    title = models.CharField(max_length=100)
    content = models.TextField()


2. 번역본 생성
```bash
python manage.py makemigrations
```

