# 太鼓の達人キーボード設定（仮称）

## はじめに

- Steam 版のドンフェスやってる？
  - よいところ: 120 fps に家庭用で初めて対応してる
  - わるいところ: キーボード設定がいまいち

## キーボード設定の何がいまいち？

- 4 個のキーしか使えない
  - 2 個のキーを面、2 個のキーを縁に割り振る
- 4 個キーのデメリット
  - 連打が遅い
    - e.g. コントローラーの場合は、4 個のキーを面、6 個のキーを縁に割り振ることができる
  - **ロール処理ができない**
    - 片手で連続して面または縁を叩くことができない

## どうすればよい？

- どうにかして 4 個のキーを面に、4 個のキーを縁に割り振りたい
  - しかし、ドンフェスの割り当て設定では達成できない
  - ではどうするか
- キーボードを押したときに、 **コントローラーを押したとみなす** ようにする

ちゃんとロール処理できてる動画:
<iframe width="560" height="315" src="https://www.youtube.com/embed/F6l3Ip0caBc?start=103" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## つまり？

- キーボードの F キーを押したとき、コントローラーの下十字キーを押したとみなす
  - 以上のような設定を 8 個のキーで設定する

![Xbox gamepad](https://upload.wikimedia.org/wikipedia/commons/1/1b/Xbox_Controller.svg)

## どうやって実現する？

- 仮想的な Xbox コントローラーを PC に認識させる
  - [djlastnight's Gaming Keyboard Splitter](https://github.com/djlastnight/KeyboardSplitterXbox) で実現できる
- 注意: このページでは上記ソフトウェアのインストール方法は説明しない
  - 頑張って調べて
