## Как создать SSH ключ
```bash
ssh-keygen -t ed25519 -C "your_email@example.com" - создание ssh ключа
в найстроках добавляем ssh ключ из файла ed25519.pub (в этом файле находится публичный ключ)
чтобы склонировать репозиторий надо: 
git clone git@github.com:username/repository.git