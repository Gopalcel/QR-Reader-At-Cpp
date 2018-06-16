# 使い方
1. `zbar`と`opencv`をインストール
2. ``` g++ qr_reader.cc  -o read `pkg-config -flags opencv` `pkg-config --libs opencv` `pkg-config --cflags zbar``pkg-config --libs zbar` ```

# 参考文献(というよりもはやコピペ元)
https://qiita.com/bohemian916/items/938efd03656f91985f7c
