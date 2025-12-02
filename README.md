# Tmux Cheatsheet (Uzbek & English)

Ushbu repository **tmux** buyruqlari va tezkor tugmachalari (shortcuts) uchun ikki tilli (O'zbek va Ingliz) ma'lumotnomani o'z ichiga oladi. Dasturchilar va serverlarda ishlovchi foydalanuvchilar uchun foydali manba.

This repository contains a bilingual (Uzbek and English) cheatsheet for essential **tmux** commands and shortcuts. It serves as a handy reference for developers and users working in server environments.

---

## - English Cheatsheet

### Tmux Commands and Shortcuts Reference

| Category | Description | Shell Command | Tmux Command | Shortcut |
| :--- | :--- | :--- | :--- | :--- |
| **Sessions** | Start a new session | `tmux new-session` | `new` | |
| **Sessions** | Start a new session or attach to an existing session named *mysession* | `tmux new-session -A -s mysession` | | |
| **Sessions** | Kill/delete the current session | | `kill-session` | |
| **Sessions** | Show all sessions | `tmux ls` | | `Ctrl + b s` |
| **Sessions** | Detach from session | | | `Ctrl + b d` |
| **Sessions** | Attach to last session | `tmux attach` | | |
| **Windows** | Create window | | | `Ctrl + b c` |
| **Windows** | Rename current window | | | `Ctrl + b ,` |
| **Windows** | Close current window | | | `Ctrl + b &` |
| **Windows** | Previous window | | | `Ctrl + b p` |
| **Windows** | Next window | | | `Ctrl + b n` |
| **Panes** | Split the current pane with a vertical line (horizontal layout) | | `split-window -h` | `Ctrl + b %` |
| **Panes** | Split the current with a horizontal line (vertical layout) | | `split-window -v` | `Ctrl + b "` |
| **Panes** | Switch to next pane | | | `Ctrl + b o` |
| **Panes** | Toggle pane zoom | | | `Ctrl + b z` |
| **Panes** | Close current pane | | | `Ctrl + b x` |
| **Copy Mode** | Enter copy mode | | | `Ctrl + b [` |
| **Copy Mode** | Paste contents of buffer_0 | | | `Ctrl + b ]` |
| **Misc** | Enter command mode | | | `Ctrl + b :` |
| **Help** | List key bindings (shortcuts) | `tmux list-keys` | `list-keys` | `Ctrl + b ?` |

---

## O'zbekcha Cheatsheet

### Tmux Buyruqlari va Tezkor Tugmachalar Ro'yxati

| Kategoriya | Tavsif | Shell Buyrug'i | Tmux Buyrug'i | Tezkor Tugmacha |
| :--- | :--- | :--- | :--- | :--- |
| **Seanslar** | Yangi seansni boshlash | `tmux new-session` | `new` | |
| **Seanslar** | Yangi seansni boshlash yoki mavjud *mysession* deb nomlangan seansga ulanish | `tmux new-session -A -s mysession` | | |
| **Seanslar** | Joriy seansni o'chirish/tugatish | | `kill-session` | |
| **Seanslar** | Barcha seanslarni ko'rsatish | `tmux ls` | | `Ctrl + b s` |
| **Seanslar** | Seansdan ajralish (Detach) | | | `Ctrl + b d` |
| **Seanslar** | Oxirgi seansga ulanish (Attach) | `tmux attach` | | |
| **Oynalar** | Oyna (Window) yaratish | | | `Ctrl + b c` |
| **Oynalar** | Joriy oynani nomini o'zgartirish | | | `Ctrl + b ,` |
| **Oynalar** | Joriy oynani yopish | | | `Ctrl + b &` |
| **Oynalar** | Oldingi oyna | | | `Ctrl + b p` |
| **Oynalar** | Keyingi oyna | | | `Ctrl + b n` |
| **Panellar** | Joriy panelni vertikal chiziq bilan bo'lish (gorizontal joylashuv) | | `split-window -h` | `Ctrl + b %` |
| **Panellar** | Joriy panelni gorizontal chiziq bilan bo'lish (vertikal joylashuv) | | `split-window -v` | `Ctrl + b "` |
| **Panellar** | Keyingi panelga o'tish | | | `Ctrl + b o` |
| **Panellar** | Panelni kattalashtirishni (zoom) almashtirish | | | `Ctrl + b z` |
| **Panellar** | Joriy panelni yopish | | | `Ctrl + b x` |
| **Nusxa olish rejimi** | Nusxa olish rejimiga kirish | | | `Ctrl + b [` |
| **Nusxa olish rejimi** | buffer_0 tarkibini joylashtirish (Paste) | | | `Ctrl + b ]` |
| **Boshqa** | Buyruq rejimiga kirish | | | `Ctrl + b :` |
| **Yordam** | Tugmalar bog'lanishlarini (shortcuts) ro'yxatini ko'rsatish | `tmux list-keys` | `list-keys` | `Ctrl + b ?` |

---
Manba/Source: https://github.com/l9c/tmux_cheat_sheet_data
