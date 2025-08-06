### 🌐 Choose your language / Выберите язык:
- [🇬🇧 English](#english-anchor)
- [🇷🇺 Русский](#russian-anchor)

---

<a name="english-anchor"></a>
### 🇬🇧 English

#### Git Workflow Steps

| Step | Action                                                       | Command                                |
|------|--------------------------------------------------------------|----------------------------------------|
| 1    | Create a repository on GitHub                                | –                                      |
| 2    | Clone the repository to your local machine                   | `git clone link`                       |
| 3    | Check the status of your local repository                    | `git status`                           |
| 4    | Create a file named `first_task.txt`                         | –                                      |
| 5    | Add the file to the staging area                             | `git add first_task.txt`              |
| 6    | Create a commit with a message                               | `git commit -m "test commit 1"`       |
| 7    | Push the commit to the remote repository                     | `git push`                             |

> **P.S.** Instead of using two separate commands — `git add <file>` and `git commit -m "your message"` —  
> you can use the shorthand `git commit -am "your message"` if you're modifying files that are already being tracked.  
> However, for new (untracked) files, you must use `git add` first — otherwise they won't be included in the commit.

---

<a name="russian-anchor"></a>
### 🇷🇺 Русский

#### Шаги работы с Git

| Шаг | Действие                                                       | Команда                                |
|-----|----------------------------------------------------------------|----------------------------------------|
| 1   | Создание репозитория на GitHub                                 | –                                      |
| 2   | Клонирование репозитория на ПК                                 | `git clone link`                       |
| 3   | Проверка состояния локального репозитория                      | `git status`                           |
| 4   | Создание файла `first_task.txt`                                | –                                      |
| 5   | Добавление файла                                               | `git add first_task.txt`              |
| 6   | Создание коммита с сообщением                                  | `git commit -m "test commit 1"`       |
| 7   | Отправка коммита на удалённый репозиторий                      | `git push`                             |

> **P.S.** Вместо двух отдельных команд `git add <файл>` и `git commit -m "комментарий"`  
> можно использовать сокращённую команду `git commit -am "комментарий"`,  
> если вы вносите изменения в уже отслеживаемые файлы.  
> Однако новые файлы необходимо сначала явно добавить с помощью `git add`, иначе они не попадут в коммит.

