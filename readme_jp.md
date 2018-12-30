# 西武40000系車両アドオン
[![lisence](https://img.shields.io/github/license/stop-pattern/seb40000.svg)](https://www.apache.org/licenses/LICENSE-2.0) ![size](https://img.shields.io/github/repo-size/stop-pattern/seb40000.svg) [![release](https://img.shields.io/github/release-pre/stop-pattern/seb40000.svg)](/releases) [![release date](https://img.shields.io/github/release-date-pre/stop-pattern/seb40000.svg)](/releases) ![downloads total](https://img.shields.io/github/downloads/stop-pattern/seb40000/total.svg)  
[![open issue](https://img.shields.io/github/issues/stop-pattern/seb40000.svg)](/issues?q=is:open) [![closed issue](https://img.shields.io/github/issues-closed/stop-pattern/seb40000.svg)](/issues?q=is:closed) [![contributors](https://img.shields.io/github/contributors/stop-pattern/seb40000.svg)](/contributors) [![last commit](https://img.shields.io/github/last-commit/stop-pattern/seb40000.svg)](/commit)	 [![last commit activity](https://img.shields.io/github/commit-activity/y/stop-pattern/seb40000.svg)](/commit)  
[![BVE](https://img.shields.io/badge/supprt-BVE-red.svg)](http://bvets.net) [![BVE](https://img.shields.io/badge/BVE-5.7≦-red.svg)](http://bvets.net)  
列車運転シミュレーションゲーム”Bve Trainsim”専用西武40000系車両アドオン  
please read [readme](/readme_en.md) if you want readme in English.  

---

## 詳細
- [**西武鉄道様**](https://www.seiburailway.jp/)の[***40000系***](https://www.seiburailway.jp/fan/zukan/40000/index.html)をmackoy様作の**列車運転シミュレーションゲーム**[***BveTrainsim***](http://bvets.net/)で使用可能なアドオン化したものです。  
- 車両アドオンに内包される車両性能は理論値です。  
- [readme](/Scenarios/stop_pattern/readme/seb40000.txt)  
- 現在鋭意製作中  

## 再現している機能
- [x] ログ出力
	- [ ] 運転曲線
	- [ ] 加減速度変化図
- [ ] 転動防止/転動防止開放
- [ ] ハンドル定速
- [ ] ハイビーム/減光
- [ ] ATO
	- [ ] TASC
	- [ ] 滑走検知（搭載？<!--加速度絶対値の急動-->
- [ ] TIS架空対応
- [ ] TIS種別拡張
- [ ] TIS停車駅外部入力対応
- [ ] ドア独立動作
- [ ] 会社線別乗降促進（搭載？
- [ ] 防護無線（搭載？

## 環境(動作・サポート)

- Windows10
    制作環境がWindows10であるため、事象の再現性の観点より勝手ながらWindows10のみとします  
- BveTs(5.7以上)

## 使用方法

1. [こちら](/releases)から最新版をダウンロード
2. 中身をBVEのScenariosフォルダ[^default_folder]へ移動
 [^default_folder]:デフォルトで`C:\Users\%UserName%\Documents\BveTs\Scenarios\`

## ライセンス(著作権表示)

当アドオンのライセンスは以下の通りとし、ライセンス内で定義される成果物とは、アドオン製作者が制作し、アドオンに内包されているすべての物のこととします。  

[Apache v2](http://www.apache.org/licenses/LICENSE-2.0)
<details>
<summary>Apache License version2.0(Apache v2)とは</summary>  
フリーソフトウェアのライセンスの一形態であり、内容は下記の通り  

必須事項
- 著作権の表示
- 変更箇所の明示

許可事項
- 商用利用
- 修正
- 配布
- 特許許可
- サブライセンス

禁止事項
- 責任免除
- 商標の使用

</details>  

```
Copyright 2018 stop_pattern

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```


当車両アドオンの使用前にライセンスを必ずお読み下さい。  
なお、利用者が当車両アドオン指定のライセンスに基づいた行動をとらない場合、当車両アドオンの利用権利を持ちません。  

## 改造及び改変

アドオンの改造、改変は当アドオン指定のライセンスにより許可されていますが、公開する際にはライセンスに基づき下記の点に従う必要があります。  

必須事項
 - 著作権の表示
 - 変更箇所の明示
禁止事項
 - 責任免除
 - 商標の使用

<br>

改造、改変の流れ  

1. forkする  
2. cloneする  
3. 改変(改造)する  
4. commitする  
5. pushする  
6. pullRequestを作成  

## 制作者
[Stop_Pattern](https://github.com/stoppattern)  

## 謝辞
BVEを開発されたmackoy様を始めとし、多くの方のお力添えをいただきこのアドオンは作成されました。  
アドオン利用者の方も含め、関わっていただいたすべての方に深く感謝します。  