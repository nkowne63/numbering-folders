# fnum

フォルダのprefixに数字をつけたり、数字を整理したりするだけの簡単なコマンドです。
cdとかするときに数字だけで飛べるようになるのでちょっと便利になります。

# fnum order

数字に欠番があったら欠番を埋めるように数字を付け直してくれます

# fnum number -n \<number\> -f \<folder_name\>

\<folder_name\>のフォルダに\<number\>の数字のプレフィックスをつけます。同じ数字があったら、それより大きいやつは全て+1されます。