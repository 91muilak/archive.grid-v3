<img title="Логотип проекта" src="https://avatars.githubusercontent.com/u/2918581?s=200&v=4" alt="Logo" width="100px" align="right" /> Grid-v3 ![](https://img.shields.io/github/package-json/var/91muilak/grid-v3?label=%20)
======
📱 Мощная система гибких сеток из [Bootstrap 3](https://bootstrap-4.ru/docs/3.4/css/#grid) для мобильных устройств, для удобной верстки и расположения элементов любых видов и размеров.

![GitHub Repo stars](https://img.shields.io/github/stars/91muilak/grid-v3?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/91muilak/grid-v3?style=social)
![GitHub Forks](https://img.shields.io/github/forks/91muilak/grid-v3?style=social)
![GitHub contributors](https://img.shields.io/github/contributors/91muilak/grid-v3?style=social&logo=github)

![Последний коммит](https://img.shields.io/github/last-commit/91muilak/grid-v3)
![Количество коммитов в год](https://img.shields.io/github/commit-activity/y/91muilak/grid-v3)
![Последний релиз](https://img.shields.io/github/v/release/91muilak/grid-v3)
![Дата последнего релиза](https://img.shields.io/github/release-date/91muilak/grid-v3)
![Количество ЯП](https://img.shields.io/github/languages/count/91muilak/grid-v3?color=fff)
![Топ ЯП](https://img.shields.io/github/languages/top/91muilak/grid-v3?color=C76494)
![Размер репозитория](https://img.shields.io/github/repo-size/91muilak/grid-v3?color=ffb600)
![Размер кода](https://img.shields.io/github/languages/code-size/91muilak/grid-v3)
[![Количество открытых issue](https://img.shields.io/github/issues-raw/91muilak/grid-v3)
![Количество закрытых issues](https://img.shields.io/github/issues-closed-raw/91muilak/grid-v3?color=354a6d)](https://github.com/91muilak/grid-v3/issues)
[![Количество открытых PR](https://img.shields.io/github/issues-pr-raw/91muilak/grid-v3?label=open%20PR%27s)
![Количество закрытых PR](https://img.shields.io/github/issues-pr-closed-raw/91muilak/grid-v3?label=closed%20PR%27s)](https://github.com/91muilak/grid-v3/pulls)
![visitors](https://visitor-badge.laobi.icu/badge?page_id=91muilak.grid-v3)

## 📥 Установка ![](https://img.shields.io/github/package-json/version/91muilak/grid-v3/main?label=%20)
Выполнить установку Grid-v3 можно склонировав весь репозиторий напрямую с GitHub или же установить через пакетный менеджер [npm](https://nodejs.org/en/download/).
### 🔴 npm
Для установки grid-v3 в проект выполните команду:
```bash
npm i @rx1310/grid-v3
```
и добавьте файл в импорт:
```scss
@import 'node_modules/@rx1310/grid-v3/grid-v3';
```

### :octocat: Git
Для клонирования проекта необходимо иметь установленный [git](https://git-scm.com/downloads). Если он установлен, то просто выполните команду в терминале:
```bash
git clone https://github.com/91muilak/grid-v3
```
и добавьте файл в импорт:
```scss
@import 'grid-v3/grid-v3';
```
### 🗂 Git Submodules
Для клонирования в качестве субмодуля также нужен установленный [git](https://git-scm.com/downloads). Если он установлен, то просто выполните команду в терминале:
```bash
git submodule add https://github.com/91muilak/grid-v3
```
и добавьте файл в импорт:
```scss
@import 'grid-v3/grid-v3';
```

## 🔧 Настройка
В пакете по умолчанию отключена генерация утилит для Flex и Spacing. Для включения этих утилит необходимо в вашем SASS-файле прописать перед импортом:
```scss
$grid-genSpacersUtils: true; // для генерации margins и paddings
$grid-genFlexUtils: true; // для генерации прочих утилит для Flex
```

## 👥 Комьюнити
[Я](https://github.com/rx1310) буду рад получить от вас фидбек или какую-либо помощь для улучшения проекта. Идеи 💡, код 👩‍💻, советы 👌 и всё что только можно - я буду рад 😊.

[![Telegram](https://img.shields.io/badge/telegram-26A5E4?logo=telegram)](https://t.me/rx1310)
[![Дискуссии](https://img.shields.io/github/discussions/91muilak/grid-v3?logo=github)](https://github.com/91muilak/grid-v3/discussions)
[![Discord](https://img.shields.io/discord/917901779394514954?color=5865F2&label=discord&logo=discord&logoColor=fff)](https://discord.gg/fvW9mHE6)

## 📜 Лицензия ![Лицензия](https://img.shields.io/github/license/91muilak/grid-v3?label=%20)
Проект распространяется по свободной [лицензии MIT](LICENSE).

```
The MIT License (MIT)

Copyright (c) 2011-2021 Twitter, Inc.
Copyright (c) 2011-2021 The Bootstrap Authors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```