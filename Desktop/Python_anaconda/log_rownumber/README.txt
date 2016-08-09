キーとして抽出する値が全て一致している
場合に、キー毎にタイムスタンプ順の連番を振る。

イメージ:SQLのウィンドウ関数
ROW_NUMBER() OVER(PARTITION BY value1, value2 ORDER BY value1 ASC)
