---
title: Funny
date: 2021-04-03T22:53:58.000+05:30
github_link: https://github.com/gurusabarish/hugo-profile
author: Riko FR
tags:
- Emoji support
bg_image: ''
description: Hahahaha
toc: 

---
Emoji dapat diaktifkan dalam proyek Hugo dalam beberapa cara.

Fungsi [emojify](https://gohugo.io/functions/emojify/) bisa langsung dipanggil di template atau [Inline Shortcodes](https://gohugo.io/templates/shortcode-templates/#inline-shortcodes) .

Untuk mengaktifkan emoji Beroperasi global, atur `enableEmoji`Ke `true`hati [Konfigurasi](https://gohugo.io/getting-started/configuration/) situs Andari, Andari Lalu DAPAT mengetik Kode singkatan emoji Langsung di Berkas Konten; misalnya

The [Emoji contekan](http://www.emoji-cheat-sheet.com/) adalah referensi yang berguna untuk emoji singkatan kode.

<hr>

**NB** Langkah-langkah di atas mengaktifkan karakter dan urutan emoji Unicode Standard di Hugo, namun rendering mesin terbang ini bertumpu pada browser dan platform. Untuk menata emoji, Anda dapat menggunakan font emoji pihak ketiga atau tumpukan font; misalnya

    .emoji {
      font-family: Apple Color Emoji, Segoe UI Emoji, NotoColorEmoji, Segoe UI Symbol, Android Emoji, EmojiSymbols;
    }

<br>

[Format penurunan harga untuk emoji](https://gist.github.com/rxaviers/7360908)