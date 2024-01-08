# README

HTML, CSS, JavaScriptで時計を描画するソース。配信用などに

## 方針

- OBSに読み込ませるソースを少なくしたいことから、CSSはHTMLの`<head>`内に直に書いている。
- オフラインでも使いたい場合を考慮し、別途フォントデータはローカル同階層ディレクトリにダウンロードする想定。

## 参考にさせていただきました
- [現在時刻をテキストでリアルタイムに表示し続ける時計を作る方法](https://www.nishishi.com/javascript-tips/realtime-clock-setinterval.html)