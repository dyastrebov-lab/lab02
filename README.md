<div align="center">
  <a href="https://github.com/dyastrebov-lab/lab02">
    <img src="https://socialify.git.ci/dyastrebov-lab/lab02/image?language=1&owner=1&name=1&stargazers=1&theme=Light" alt="lab02" width="640" />
  </a>
</div>

<div align="center">

![Last commit](https://img.shields.io/github/last-commit/dyastrebov-lab/lab02)
![Repo Size](https://img.shields.io/github/repo-size/dyastrebov-lab/lab02)
![License](https://img.shields.io/github/license/dyastrebov-lab/lab02)
![Python](https://img.shields.io/static/v1?logo=python&logoColor=fff&label=&message=Python&color=363939&style=flat)
![Git](https://img.shields.io/static/v1?logo=git&logoColor=fff&label=&message=Git&color=363939&style=flat)
![GnuPG](https://img.shields.io/static/v1?logo=gnuprivacyguard&logoColor=fff&label=&message=GnuPG&color=363939&style=flat)

</div>

В работе изучены основы администрирования UNIX-подобных систем на примере дистрибутива Ubuntu: базовые команды, управление правами доступа, специальные биты, POSIX ACL и процессы.

**Что отработано:** основные команды Linux, исправление ошибок в скрипте на Python, управление правами доступа, принципы работы специальных битов (SUID, sticky bit), POSIX ACL, анализ процессов (`tty`/`pts`).

**Стек:** Git, GitHub CLI, Python 3.14.4, pygame-ce, GnuPG

***

### Окружение

- Ubuntu 26.04 LTS
- Python 3.14.4
- git 2.53.0
- gh 2.46.0
- gpg (GnuPG) 2.4.8

### Установка

```bash
git clone git@github.com:dyastrebov-lab/lab02.git
cd lab02
python3 -m venv .venv
source .venv/bin/activate
pip install pygame-ce
```

### Использование

```bash
python3 pygamesteel_fixed.py
python3 exmpl_hello.py
```

***

### Структура

```text
lab02
├── .gitignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE.md
├── NOTICE.md
├── README.md
├── SECURITY.md
├── exmpl_hello.py        # учебный скрипт из задания
├── nmapres.txt           # файл для результатов nmap (для следующей ЛР)
├── pygamesteel.py        # исходный скрипт с ошибками из задания
├── pygamesteel_fixed.py  # исправленная версия скрипта
└── screen                # тестовый файл для отработки прав доступа
```

***

### Соответствие требованиям

- Все коммиты подписаны GPG (`git commit -S`), на GitHub — статус **Verified**
- Вся работа ведётся в ветке `develop`
- История разбита на атомарные коммиты
- Изменения вливаются через Pull Request: `develop → master`
- Все операции выполнены из терминала, включая работу с GitHub через `gh`
- Репозиторий содержит `.gitignore`, `LICENSE.md`, `NOTICE.md`, `SECURITY.md`,
  `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`

***

### Лицензия

Apache License 2.0 — см. [LICENSE.md](LICENSE.md) и [NOTICE.md](NOTICE.md).
