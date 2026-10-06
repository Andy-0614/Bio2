---
title: "我好像是一隻企鵝"
date: 2026-10-04T12:00:00+08:00
draft: false
tags: [範例]
ShowToc: true
---

<img src="/example.jpg" alt="小包" width="50%">

**小包**
我覺得我會飛。

---

## 文字大小

```markdown
# 一級標題
## 二級標題
### 三級標題
#### 四級標題
##### 五級標題
###### 六級標題
```

# 一級標題
## 二級標題
### 三級標題
#### 四級標題
##### 五級標題
###### 六級標題

---

## 文字效果

```markdown
**粗體**

*斜體*

***粗斜體***

~~刪除線~~

`行內程式碼`
```

**粗體**

*斜體*

***粗斜體***

~~刪除線~~

`行內程式碼`

---

## 清單

```markdown
- 香草 $30
- 抹茶 $100000
  - 加牛奶 $100000000

1. 香草
2. 抹茶
```

- 香草 $30
- 抹茶 $100000
  - 加牛奶 $100000000

1. 香草
2. 抹茶

---

## 選框

```markdown
- [x] 蘋果
- [ ] 香蕉
```

- [x] 蘋果
- [ ] 香蕉

---

## 表格

```markdown
| 靠左 | 置中 | 靠右 |
| :--- | :---: | ---: |
| 雞蛋 | 牛奶 | 麵包 |
| 白飯 | 蛋糕 | 餅乾 |
```

| 靠左 | 置中 | 靠右 |
| :--- | :---: | ---: |
| 雞蛋 | 牛奶 | 麵包 |
| 白飯 | 蛋糕 | 餅乾 |

---

## 圖片大小

Markdown 原生的圖片 `![小包](/example.jpg)` 不能調整大小，要改用 HTML 的 `<img>`，用 `width` 設定寬度。

```html
<img src="/example.jpg" alt="小包" width="30%">
```

<img src="/example.jpg" alt="小包" width="30%">

---

## 文字上色

Markdown 沒有顏色語法，要改用 HTML 的 `<span>`。

```html
<span style="color:#c9a227">香草</span>

<span style="color:#5a8f29">抹茶</span>

<span style="background:#5a8f29;color:white">抹茶冰淇淋</span>
```

<span style="color:#c9a227">香草</span>

<span style="color:#5a8f29">抹茶</span>

<span style="background:#5a8f29;color:white">抹茶冰淇淋</span>

---

## 連結

```markdown
[Markdown 詳細語法](https://markdown.tw/)

[Markdown 線上編輯器](https://example.com)

```

[Markdown 詳細語法](https://markdown.tw/)

[Markdown 線上編輯器](https://example.com)
