﻿# Try Kernel-S

## 概要

Try Kernel-Sはマイコン用のSMP方式マルチコア対応の超軽量リアルタイムOSです。リアルタイムOSの極々基本的な機能のみを提供します。
Try Kernel-Sは、CQ出版(株) **Interface 2024年11月号の特集「ゼロから作るマルチコアOS」** に向けて作成し、このリポジトリでメンテしています。
この記事の配布プログラムは以下から入手できます。

<https://github.com/ytoyoyama/interface_trykernel_2>

サンプルのアプリケーションはこの配布プログラムを参照ください。

## 対象H/W・開発ツールなど

- RaspberryPy Pico , Pico W
- GNU Arm Embedded GCC

## ビルド方法
対象H/W向けに全ソースコードをコンパイル、リンクしてください。  
以下の各開発環境については、それぞれのブランチを参照してください。  

- Eclipse Embedded CDTの場合 [project_eclipse](https://github.com/ytoyoyama/trykernel-s/tree/project_eclipse)
- Makeの場合   [build_make](https://github.com/ytoyoyama/trykernel-s/tree/build_make)

## ライセンスについて

本プログラムはMITライセンスの下でオープンソースとして公開します。著作権および許諾表示を記載すれば、非営利、商用を問わず、使用、改変、複製、再頒布が可能な制限の緩いライセンスですので、本プログラムをOSの自作に活用いただけたらと思います。ライセンスの詳細については、同梱のLICENSEをご参照ください。  
ただし、ブートコードの一部でPico C/C++ SDKのオブジェクトコードを利用してますので、それについてはPico C/C++ SDKのライセンスが適用されます。ソースファイルの冒頭に記載したライセンスに従ってください。このライセンスも厳しい制約はありません。該当するファイルは以下です。  

boot\boot2.c  
