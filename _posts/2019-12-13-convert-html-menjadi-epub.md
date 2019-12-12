---
layout: post
title: Convert HTML Menjadi ePub
subtitle : Cocok buat yang mau upload buku ke Play Book
tags: [Buku]
author: Zen
comments : True
---

```bash
ebook-convert "awal.html" "hasil.epub" --output-profile="sony" --cover="cover.png" --level1-toc "//h:h1" --level2-toc "//h:h2" --level3-toc "//h:h3"

```