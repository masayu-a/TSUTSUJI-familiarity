# TSUTSUJI-familiarity (version 2.0.0) (2024/02/11)

## Description
日本語機能表現辞書『つつじ』 version 1.1に対して、クラウドソーシングにより親密度情報・位相情報を付与したもの

## Features 

### TSUTSUJI.txt

1行目がヘッダ

- 1列目：WID 調査時のID
- 2列目：WORD 表層形
- 3列目：LABEL 『つつじ』のラベル
- 4列目：FACTOR 印象評定の属性
- 5列目：VALUE 印象評定値

### 機能語印象評定情報.xlsx

#### 元データ

1行目がヘッダ

- 1列目：WID 調査時のID
- 2列目：WORD 表層形
- 3列目：LABEL 『つつじ』のラベル
- 4列目：FACTOR 印象評定の属性
- 5列目：VALUE 印象評定値

#### 集計結果

1行目がヘッダ

- 1列目：WORD 表層形
- 2列目：KNOW 印象評定:「知っている」
- 3列目：LISTEN 印象評定:「聞く」
- 4列目：READ 印象評定:「読む」
- 5列目：SPEAK 印象評定:「話す」
- 6列目：WRITE 印象評定:「書く」
- 7列目：5評定平均: (KNOW+LISTEN+READ+SPEAK+WRITE)/5
- 8列目：書記 印象評定: READ+WRITE
- 10列目：音声 印象評定: LISTEN+SPEAK
- 11列目：生産 印象評定: SPEAK+WRITE
- 12列目：受容 印象評定: LISTEN+READ
- 13列目：書記-音声: READ+WRITE-LISTEN-SPEAK
- 14列目：生産-受容: SPEAK+WRITE-LISTEN-READ


## References

松吉俊、佐藤理史、宇津呂武仁 (2007) 日本語機能表現辞書の編纂, 『自然言語処理』, 14(5), pp.123-146, https://doi.org/10.5715/jnlp.14.5_123

Bocheng Chen, Masayuki Asahara (2023) Word Familiarity Rate Estimation for Japanese Functional Words Using a Bayesian Linear Mixed Model, 
Proceedings of the Pacific Asia Conference on Language, Information and Computation (PACLIC 37).

## Credit
- つつじ version 1.1  -- 日本語機能表現の辞書
  松吉俊、佐藤理史 2016/04/20
  CC BY-SA 3.0 
  https://sites.google.com/edu.teu.ac.jp/cl-lab/研究/言語資源/日本語機能表現辞書つつじ
- TSUTSUJI-familiarity -- つつじ単語親密度情報 -- version 2.0.0
  国立国語研究所   2024/02/11

## ChangeLog

### 2.0.0 (2024/02/11)

- L9 までの 23671 語を追加調査 (2024/01/01)
- 集計方法を変更

### 1.0.0 (2023/11/03)

- L7 までの 6396 表層形を調査 (2022/12/29)

## Contact
masayu-a@ninjal.ac.jp
