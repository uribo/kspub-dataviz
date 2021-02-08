正誤表
===========================

現時点で判明している誤植などを掲載しています。

| 該当箇所 | 誤 | 正 | issue | 備考 | 対応 |
|:---------|----|----|----|:-----|:-----|
| p.109, 110, 114 (図3.8, 図3.9, 図3.13) | コードが`geom_smooth(method = "gam")`の記述であるのに対して、描画される図では直線が引かれる。 | **図の誤り**。コードを実行するとGAM平滑化曲線が描画される。 | [#3](https://github.com/uribo/kspub-dataviz/issues/3) | ただし原著でも直線のため、原著者への確認中。 | | 
| p.139 タイトル | 回りくどく度数分布表を描いてみる | 度数分布を回りくどく描いてみる | [#2](https://github.com/uribo/kspub-dataviz/issues/2) | | |
| p.169 本文 | 実行してみましょう（図5.9). | 実行してみましょう. | - | | |
| p.285 脚注 | colorblinder | colorblindr | [#1](https://github.com/uribo/kspub-dataviz/issues/1) | colorblindrパッケージはCRAN未登録(2020年2月3日時点)。利用する際はGitHubの[リポジトリ](https://github.com/clauswilke/colorblindr)からのインストールが必要。 | |
