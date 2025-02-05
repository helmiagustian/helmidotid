---
title: "Ssh"
date: 2023-04-25T20:26:48+07:00
draft: false
---

## Generating SSH ed25519 Key

> ssh-keygen -t ed25519

## Copy the key to a server

> ssh-copy-id -F ~/.ssh/id_ed25519.pub user@host
