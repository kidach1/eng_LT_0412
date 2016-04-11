# 最近のAndroidを取り巻くなんたら

谷口

---

## Slideck

* 本日もっとも有用な情報
* 待望のMarkdownプレゼンテーション！

<https://slideck.io/>

---

## 最も有用な情報終わり

---

## Android

---

![android arch](http://image.slidesharecdn.com/android-presentation-110627072852-phpapp02/95/android-development-the-basics-6-728.jpg?cb=1309160008)

---

## Android何で書く？

* Java
* Scala
* Kotlin

---

## Java

oh...

---

## Scala

言語としては良いっぽい

* compile time
* 64k問題
* gradleとの連携

ちょっとないかなー

AndroidでScalaを使う際の問題点と対策
<http://www.slideshare.net/saturday06/pixiv0905x2>

---

## Kotlin

* Better Java - Modern Syntax, JVM lang 
* By JetBrains
* 2016/02, ver 1.0 released!!

---

Advanced Kotlin for Android #DroidKaigi
<https://speakerdeck.com/ntaro/advanced-kotlin-for-android-number-droidkaigi-number-droidkaigib>

---

## Kotlinの勢い

![kotlin@google](https://qiita-image-store.s3.amazonaws.com/0/48274/8d64734b-37b0-1042-5d1d-e43630e11649.png)



```
## This is an H2 Title

Description...

The horizontal slide separator characters are '---'

```

* Easy to write
* Good for showing programming code

---

## reveal.js Wrapper Apps

* [App::revealup](https://metacpan.org/pod/App::revealup)
* [revealgo](https://github.com/yusukebe/revealgo)

These apps are useful for previwing on **localhost**.

But only on **localhost**.

---

## I need online tool

* Online access to the slides
* Share URL quickly
* Inspired by `godoc.org`

---

## Slideck

---

![slideck](images/slideck_ss.png)

---

## Feature

Markdown on GitHub repo will be showed as slideshow

* Compatible with reveal.js/revealgo
* Embeded assets such as image files
* Support private repo with GitHub sign in
* Sanitize generated HTML from Markdown

---

## Usage

* Write formatted Markdown text
* `git push` to your own GitHub repo
* Access to `/github.com/{owner}/{repo}/{path}`

---

## Example

* This Markdown Path : `github.com/yusukebe/slides/slideck.md`
* Slideck URL : <https://slideck.io/github.com/yusukebe/slides/slideck.md>

---

## Implementation

* Golang + Heroku

```
"github.com/google/go-github/github"
"github.com/microcosm-cc/bluemonday"
"github.com/russross/blackfriday"
"golang.org/x/oauth2"
"golang.org/x/oauth2/github"
"github.com/ymichael/sessions"
"github.com/zenazn/goji"
"github.com/zenazn/goji/web"
```

---

## Try Slideck now!

<https://slideck.io>
