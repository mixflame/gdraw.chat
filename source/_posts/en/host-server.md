---
title: host-server
author:
  job: null
  name: null
  link: null
  photo: null
  email: null
  phone: null
date: 2020-08-25 14:34:07
updated: 2020-08-25 14:34:07
lang:
photo:
description:
tags:
categories:
- Home
---


Anyone can host a GlobalChat server. The current recommended way is to use Ubuntu snaps with Linux.


`snap install --beta crystal-gchat-server`

`crystal-gchat-server.change-passwords -i`

`crystal-gchat-server`

And then add the necessary systemd service file to keep it running. Don't run it as root, just to be safe.