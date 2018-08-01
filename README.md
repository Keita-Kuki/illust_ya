# illust_ya
研究室内実験用ソフトウェア  
Python 3.6.2

# initialize

```sh
git clone https://github.com/Keita-Kuki/illust_ya.git
cd illust_ya
mkdir assets
```

assets内にexcelファイルと画像フォルダを移動  
excelファイルをCSV形式でエクスポート

```sh
pip install -r requirements.txt
```

# how to use
```sh
jupyter notebook
```

ファイルパスを変更する
```python
# ファイルパス（要変更）
csv_path = "assets/CSV_FILE.csv"
image_directory_path = "assets/IMAGE_DIRECTORY"
```

main()を実行し、訳語と画像があっていれば`d`、あっていなければ`f`を入力して`Enter`  
(文字はtrue_char, false_charで変更可能)

結果は`result.csv`に保存される  
中断しても途中から再開される  
