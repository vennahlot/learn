# learn

Interactive, bilingual (English / 简体中文) lessons that teach by stepping through an example.
交互式双语小课程：每一课用一个例子一步一步讲。

**Open it:** https://vennahlot.github.io/learn/

| Lesson | Link |
|---|---|
| Household money → the three financial statements / 家庭收支 → 三张财务报表 | [English](https://vennahlot.github.io/learn/household-finance/?lang=en) · [中文](https://vennahlot.github.io/learn/household-finance/?lang=zh) |
| How search works: the inverted index / 搜索是怎么工作的：倒排索引 | [English](https://vennahlot.github.io/learn/inverted-index/?lang=en) · [中文](https://vennahlot.github.io/learn/inverted-index/?lang=zh) |
| How a Qimen Dunjia chart is cast / 奇门遁甲是怎么排盘的 | [English](https://vennahlot.github.io/learn/qimen-dunjia/?lang=en) · [中文](https://vennahlot.github.io/learn/qimen-dunjia/?lang=zh) |
| How a Liuyao hexagram is cast / 六爻是怎么起卦装卦的 | [English](https://vennahlot.github.io/learn/liuyao/?lang=en) · [中文](https://vennahlot.github.io/learn/liuyao/?lang=zh) |

## How it is built

- One folder per lesson, each with a single self-contained `index.html` (plain HTML, CSS and
  JavaScript, no build step, no dependencies). Open the file in a browser to run it.
- `?lang=en` or `?lang=zh` picks the language; otherwise the last choice (saved in the browser),
  then the browser's language. The choice is shared across lessons (`localStorage` key `learn-lang`).
- Works on phones: lessons switch to a one-column layout at 700 px and below.
- GitHub Pages serves `main` as is (`.nojekyll`). A push to `main` is a deploy.

## Add a lesson

1. Create `<lesson>/index.html`.
2. Add an entry to `LESSONS` in the root `index.html` and a row to the table above.
