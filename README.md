## Работа с удаленными репозиториями.
1. Создать аккаунт на Github.
2. Создать локальный репозиторий.  
3. Создать удаленный репозиторий. Нажать на плюсик в профиле на Github, создать новый репозиторый, дать имя репозиторию.
4. Связать удаленный репозиторий с локальным при помощи трех предложенных команд на Github.
```
git remote add origin https://github.com/DenisMS63/111.git - связка локального и удаленного репозиториев.
git branch -M main - переименовывание ветки master в main.
git push -u origin main - отправка локальных изменений в удаленный репозиторий.
```
Добавить удаленный репозиторий к проекту
```
git remote add <имя репозитория> <url-адрес репозитория в сети>
```
```C#
while (count > 0)
{
count--;
}
```
Для получения и слияния изменений из удаленного репозитория используется команда `git pull`
