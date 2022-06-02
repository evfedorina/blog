---
title: Управление версиями GIT
subtitle: Всем снова здравствуйте, в этом посте мы поговорим о GIT

# Summary for listings and search engines
summary: Узнаем больше про GIT

# Link this post with a project
projects: []

date: 2022-05-04T11:19:14+03:00
lastmod: 2022-05-04T11:19:14+03:00
featured: false
draft: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/Yh2Y8avvPec)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin
  - 吳恩達

tags:
  - Academic
  - 开源

categories:
  - Demo
  - 教程
---

## Overview
 Git – это разновидность VCS (Version Control System). А VCS – это программа для работы с постоянно изменяющейся информацией. Такое ПО может хранить множество версий одного и того же файла (документа) и возвращаться к более раннему состоянию (версии).

Например, код пишут четыре программиста. Они работают в разных местах, с разных компьютеров, в разное время. VCS сохраняет все изменения, внесенные всеми программистами, и в любой момент можно вернуться к версии, созданной три дня или месяц назад.

Какие VCS есть в природе:

- собственно Git;
- SVN;
- Mercurial;
- Team Foundation Server.

Все они делятся на два типа:

- распределенные (Git, Mercurial) – изменения хранятся в локальных хранилищах компьютеров и оттуда синхронизируются с другими компьютерами;
- централизованные (CVS, SVN) – все данные хранятся на центральном сервере, и оттуда каждый локальный компьютер получает обновленные данные.

Git относится к распределенным системам, поэтому не зависит от центрального сервера, где хранятся файлы. Git сохраняет данные в локальном репозитории. Что такое репозиторий Git? Это каталог на жестком диске рабочего компьютера программиста. Для большей стабильности и ускорения синхронизации разных версий проекта локальный репозиторий хранят онлайн в специальных сервисах: Github, Gitlab, Bitbucket.
