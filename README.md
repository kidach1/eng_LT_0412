### 最近のAndroidを取り巻くなんたら

谷口

---

## Slideck

* 本日もっとも有用な情報
* 待望のMarkdownプレゼンテーション！

<https://slideck.io/>

---

最も有用な情報終わり

---

= Android = 

---

![android arch](http://image.slidesharecdn.com/android-presentation-110627072852-phpapp02/95/android-development-the-basics-6-728.jpg?cb=1309160008)

---

Android, 何で書く？

* Java
* Scala
* Kotlin

---

Java

oh...

---

Scala

言語としては良いっぽい

* compile time
* 64k問題
* gradleとの連携

けどちょっとないかなー

<http://www.slideshare.net/saturday06/pixiv0905x2>

---

Kotlin

* Better Java - Modern Syntax, JVM lang 
* By JetBrains
* 2016 / 02, ver 1.0 released!!

---

Advanced Kotlin for Android #DroidKaigi
<https://speakerdeck.com/ntaro/advanced-kotlin-for-android-number-droidkaigi-number-droidkaigib>

---

Kotlinの勢い

![kotlin@google](https://qiita-image-store.s3.amazonaws.com/0/48274/8d64734b-37b0-1042-5d1d-e43630e11649.png)


---

Kotlinの勢い

![kotlin@kapt](https://qiita-image-store.s3.amazonaws.com/0/48274/9ac31654-247b-32da-873e-886b1714812a.png)

---

ところが

---

![jack1](https://qiita-image-store.s3.amazonaws.com/0/48274/504ed0e7-c0bf-f50a-1d59-7f392bd357ca.png)

![jack2](https://qiita-image-store.s3.amazonaws.com/0/48274/17342076-ac39-9b8d-4e16-cd8f441db2bb.png)

---


![suddenly_jack](https://qiita-image-store.s3.amazonaws.com/0/48274/4ca569d1-afbe-11ad-d93f-986d55436351.png)


---

突然のアーキテクチャ刷新

![jack_arch1](https://source.android.com/images/jack-overview.png)

---

![android arch](http://image.slidesharecdn.com/android-presentation-110627072852-phpapp02/95/android-development-the-basics-6-728.jpg?cb=1309160008)

---

Jack & Jill

2016/3/10

* Completely open source
* Speeds compilation time
* Handles shrinking, obfuscation, repackaging and multidex
* Java8!!!

https://source.android.com/source/jack.html

---

良いことだけじゃない

![jack_dark_side](https://qiita-image-store.s3.amazonaws.com/0/48274/a4a699d5-944a-66c9-41b7-02b7869e2fe1.png)


---

Jack's Downsides

* Transform API is not supported by Jack
* Annotation processing is not currently supported by Jack
* Lint detectors which operate on a Java bytecode level are not supported
* Jack is currently slower than javac + dx

---


そして何より…


---

![kotlin_jack1](https://qiita-image-store.s3.amazonaws.com/0/48274/1024969a-e193-93cc-834c-c3957dd7976d.png)

![kotlin_jack2](https://qiita-image-store.s3.amazonaws.com/0/48274/07f945fc-a6d0-cc2a-9aa7-4411a6be07fd.png)

突然のKotlinオワコン説

---

### why?

![jack_arch2](https://qiita-image-store.s3.amazonaws.com/0/48274/88fb96b4-536d-3375-5bca-ad1c27063f7c.png)

* jackでは(kotlincで吐いた).classファイルはサポートされない
* Jillを用いたビルドではエラー
* kotlinは.jackを吐けない

---

![jack_arch3](https://qiita-image-store.s3.amazonaws.com/0/48274/411f2659-a28f-9d98-2b8b-03bbd6349267.png)


---

Kotlin（と、Kotlinで書いてる現行プロダクト）の
運命やいかに？

続報を待て！

![dounaru_kotlin](https://qiita-image-store.s3.amazonaws.com/0/48274/f7e49b70-6777-4d47-b1bf-04fa3f1a2d45.png)


---

続報ありました


![dounaru_kotlin](https://qiita-image-store.s3.amazonaws.com/0/48274/6bcb55e3-327f-ff77-8abc-3838749b068d.png)

---

2016/3/30

![kounaru_kotlin](https://qiita-image-store.s3.amazonaws.com/0/48274/2edff468-973a-bcea-1f88-e78c9c752bbf.png)

* kotlinが吐いたbytecodeをjillで扱えるように、googleと一緒にがんばります！！１

---

Forever Kotlin!

---


次回（未定）

もうswiftでいんじゃね？ Swift@Android

![android_swift](https://qiita-image-store.s3.amazonaws.com/0/48274/f99c4d08-b905-5a5c-8639-1fa662d9f902.png)

---

次回（未定）その2

もうC#でいんじゃね？Xamarin.Android

![android_xamarin](https://qiita-image-store.s3.amazonaws.com/0/48274/7d64ca11-e25d-f4f2-decc-f5985feaedbc.png)

![android_xamarin](https://qiita-image-store.s3.amazonaws.com/0/48274/3ac66130-8674-2dce-18dc-07d3f0dba524.png)

---

Thank You!

