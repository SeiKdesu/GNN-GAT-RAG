# 困っていること


推論時の実行で、C:\Users\rsmkc\Documents\keito\RAG\evaluation1\results\KGQA-GNN-RAG\rearev-sbert\RoG-cwq\RoG\test\results_gen_rule_path_RoG-cwq_RoG_test_predictions_3_False_jsonl\False\predictions.jsonl
1問ずつ質問と推論のjsonファイルが出力されると認識しています。その中で、質問数が多くなると、だんだんVRAMの使用量が増します。私の認識では1質問終わるごとにVRAMの解放すれば、全ての質問の推論に時間がかかると思います。1質問終了するごとに、VRAMのメモリを解放するのは、よろしいのでしょうか。実装的にまた実装が困難です。

それとも、トークン数が後ろの質問であればあるほど、ましてしまっているのか？

途中までは、推論できるのですが最後までいかず、out of memoryが起きてしまう状態です。
# 実行方法

https://drive.google.com/drive/folders/1d5cCqs_oGsZPDYZx56NofaBi-Bc78rtn?usp=sharing

このファイルのresultsをダウンロードする

このリポジトリの一番上の階層へ貼り付け（src,scripts,prompts)と同じ階層です。
 

```
bash scripts/rag-reasoning.sh
```
