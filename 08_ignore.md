[<К  СОДЕРЖАНИЮ](/readme.md)

# Настройка игнорируемых файлов для одного репозитория

Вы можете создать ***.gitignore*** файл в корневом каталоге репозитория, чтобы сообщить Git, какие файлы и каталоги игнорировать при фиксации. Чтобы предоставить общий доступ к правилам игнорировать другим пользователям, которые клонировали репозиторий, зафиксируйте .gitignore файл в репозитории.

GitHub поддерживает официальный список рекомендуемых .gitignore файлов для многих популярных операционных систем, сред и языков в общедоступный репозиторий ***github/gitignore***. Вы также можете использовать [Специальный сервис - gitignore.io](gitignore.io) для создания .gitignore файла для операционной системы, языка программирования или интегрированной среды разработки. 

## Порядок действий
1 . Откройте Терминал.

2 . Перейдите к расположению репозитория Git.
3 . Создайте файл `.gitignore` для репозитория:
```
touch .gitignore
```
Если команда будет выполнена успешно, она не выведет никаких данных.  
4 . Выполняем правку файла.