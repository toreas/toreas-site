---
layout: default
title: Book 1 Page

use: [ book_1_chapters ]

---

# Book 1 Title here

## Chapters

<ul>
    {% for chapter in data.book_1_chapters %}
        <li><a href="{{ chapter.url }}">{{ chapter.title }}</a></li>
    {% endfor %}
</ul>

## Stuff and things

[Buy the book](/book-1-title/buy/)

[Download the Book](/book-1-title/download/)
