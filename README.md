COBOL練習用に作成しました。
実行環境は、UbuntuでOpenCOBOL + OpenSourceCOBOL を使用しています。

覚書
**.cblファイルを作成し、cobc -x **.cblで実行ファイルができるようですね。
実行時に-Version mismatchが発生した場合は、sudo ldconfigコマンドを実行すれば解消しそうです。もしくはhash -rで。
