正誤表
===========================

現時点で判明している誤植などを掲載しています。

| 該当箇所 | 誤 | 正 | issue | 備考 | 対応 |
|:---------|----|----|----|:-----|:-----|
| p.57　本文 | 面責 | 面積 | [#11](https://github.com/uribo/kspub-dataviz/issues/11) | | |
| p.109, 110, 114 (図3.8, 図3.9, 図3.13) | コードが`geom_smooth(method = "gam")`の記述であるのに対して、描画される図では直線が引かれる。 | **図の誤り**。コードを実行するとGAM平滑化曲線が描画される。 | [#3](https://github.com/uribo/kspub-dataviz/issues/3) | ただし原著でも直線のため、原著者への確認中。 | | 
| p.139 タイトル | 回りくどく度数分布表を描いてみる | 度数分布を回りくどく描いてみる | [#2](https://github.com/uribo/kspub-dataviz/issues/2) | | |
| p.166-7 5.6 | 図とコードの不一致 | Web版原著のコードと一致する図への差し替え予定 | [#6](https://github.com/uribo/kspub-dataviz/issues/6) | | |
| p.169 本文 | 実行してみましょう（図5.9). | 実行してみましょう. | - | | |
| p.171 図5.12のためのコード | `geom_jitter(widt = 0.15)` | `geom_jitter(width = 0.15)` | [#4](https://github.com/uribo/kspub-dataviz/issues/4) | | | 
| p.196 図5.26 | 図5.26として掲載の図 | 図5.26コード実行時に出力される図（未掲載） | [#5](https://github.com/uribo/kspub-dataviz/issues/5) | | |  
| p.202 図6.1 legend | 直線を追加 | 回帰直線・回帰曲線を追加 | [#8](https://github.com/uribo/kspub-dataviz/issues/8) | | |  
| p.241-242 図6.12, 図6.13| 図の誤り 年代表記が左揃えにならない | 図の誤り 年代表記が左揃えにならない | [#９](https://github.com/uribo/kspub-dataviz/issues/9) | 要原著者への確認 | |  
| p.241-242 図6.12, 図6.13| タイトルの日本語化・サブタイトル抜け |コード内: title = "Educational Attainment by Race" → title = "人種別の教育歴",  コード内サブタイトルママ,  図内タイトル: 人種別の教育歴,   サブタイトル: GSS 1976-2016  へ修正| [#9](https://github.com/uribo/kspub-dataviz/issues/9) | | |  
| p.263 図7.13 タイトル | 人口密度の高い地域 | 人口密度の低い地域 | [#10](https://github.com/uribo/kspub-dataviz/issues/10) | | |
| p.285 脚注 | colorblinder | colorblindr | [#1](https://github.com/uribo/kspub-dataviz/issues/1) | colorblindrパッケージはCRAN未登録(2020年2月3日時点)。利用する際はGitHubの[リポジトリ](https://github.com/clauswilke/colorblindr)からのインストールが必要。 | |
| p.298 本文 | geom_deinsity_ridges()関数 | geom_density_ridges()関数 | [#4](https://github.com/uribo/kspub-dataviz/issues/4) | | |
| p.299 本文 | 1.5超から4.1超 | 1.5兆から4.1兆 | [#4](https://github.com/uribo/kspub-dataviz/issues/4) | | |
| p.302 本文 | namest_to引数 | names_to引数 | [#4](https://github.com/uribo/kspub-dataviz/issues/4) | | |
