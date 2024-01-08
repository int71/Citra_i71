# 概要
「Citra/i71」は、Nintendo 3DSエミュレータ「Citra」( https://github.com/citra-emu )を、int71こと「整数71」( https://www.youtube.com/@int71 )がカスタマイズしたものです。

カスタマイズ範囲は、映像、音声、インタフェイス、入力、その他機能およびバグ修正に及びます。
詳細は「Customize(J).txt」を参照ください。

# 登録されているファイルについて
ディレクトリ「nnnn」および「nnnn.org」の数字は「citra-canary」のコミット番号に対応します。
ディレクトリ「nnnn」配下のファイルが「整数71」修正版で、「nnnn.org」配下は比較用にオリジナルのままです。

「nnnn」配下の修正対象ファイルは、下記拡張子のファイルになります。
特に「README.md」は修正しておらず、オリジナルのままです。

- .qrc
- .cpp
- .h
- .c
- .ui
- .rc

各ディレクトリ配下の「Release.7z」は、「整数71」修正版、オリジナル版それぞれの、リリース実行バイナリになります。

# ビルドについて
VisualStudioによるWindows(x64)向け実行バイナリ作成方法を「HowtoBuild(J).txt」に記載していますので、ご参照ください。

# 本家「Citra」( https://github.com/citra-emu )との関係
GPLv2での公開ではありますが、あくまで個人的カスタマイズ版の位置づけであり、今のところ本家へのプルリクは予定しておらず、「Citra/i71」をブランチとして伸ばす予定もありません。

※えげつない直し方している箇所も多いため

ただし、本家更新に伴い「nnnn」および「nnnn.org」ディレクトリが増えていく可能性はあります。

# ライセンス
「Citra/i71」はオリジナル「Citra」に準じ、GPLv2(もしくは以降の版)とします。「LICENSE.txt」を参照ください。
これはオリジナル「Citra」のもの( https://github.com/citra-emu/citra/blob/master/license.txt )と同一です。
