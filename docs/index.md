---
layout: default
title: 吉里吉里Z Ver.2
---

## 吉里吉里Z Ver.2 について

吉里吉里Z Ver.2 (マルチプラットフォーム版) は、Windows/Androidで動作する吉里吉里Zです。  
現状、従来のVer1.X系の吉里吉里Zとは互換性はやや低いですが、将来的に一部例外を除いてそのまま移行できるよう互換性を高める予定です。  
また、従来のソフトウェアによる描画(Layer)に加えて、ハードウェア(OpenGL ES2.0/3.0)による描画機能も加えられています。  
Windowsであれば強力なCPUにより力任せの処理もある程度可能ですが、非力なAndroid環境では苦しい場面も予想されます。  
Androidではなるべくハードウェア(GPU)を使用し快適に動作するよう書き換えた方がストレスなくプレイできるようになります。  
当然、Windowsでもハードウェア(GPU)が使われるようになるので、従来よりも低CPU負荷でより複雑で多彩な演出も可能になります。  
従来のスクリプトそのままを移行することはまだ出来ませんが、GPUを利用する描画への書き換えを行う方が、Android/Windows共に快適に動作するため、GPU描画への移行を推奨します。

## ダウンロード

* [リリース](https://github.com/krkrz/multi_platform_design/releases)

## マルチプラットフォーム版APIリファレンス

* [APIリファレンス](https://krkrz.github.io/multi_platform_design/apiref/)

## 対応プラットフォーム

### Windows
* Windows 7以降
* DirectX 11必須

### Android
* Android 4.4以降
* OpenGL ES3.0以降推奨(2.0必須)

## リポジトリ

* [本体はdev_multi_platformブランチ](https://github.com/krkrz/krkrz/tree/dev_multi_platform)
* [KAGΣ(新描画APIサンプル実装)](https://github.com/krkrz/KAGSigma)

## マルチプラットフォーム版に関する各種説明

* [Android版のリリース(ビルド)方法](https://krkrz.github.io/multi_platform_design/develop_android.html)
* [Windows版のビルド方法](https://krkrz.github.io/multi_platform_design/build_windows.html)
* [動画再生機能](https://krkrz.github.io/multi_platform_design/video_overlay.html)
* [プラグインの作り方/利用方法](https://krkrz.github.io/android_plugins/)
* [サウンド](https://krkrz.github.io/multi_platform_design/audio.html)
* [シェーダーの使い方](https://krkrz.github.io/multi_platform_design/shader_program.html)
* [移植時の注意点](https://krkrz.github.io/multi_platform_design/cautionary_note.html)
