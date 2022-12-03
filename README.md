Author:
    yusyamas (42Tokyo C Piscine 2022/10 Fail)

git url:
  git@vogsphere-v2.42tokyo.jp:vogsphere/intra-uuid-fdc3c268-f2a2-4fd4-8014-eeb6fcae577e-4488330-asimmel

試験結果:
  ボーナスを選ばず100pts
  n = 4のみ
  dfsと順列全探索を組み合わせた解法だが、計算量の改善がまだできる(n=5はわかるがそれ以降がわからない)
改善点:
  横が1,2,3,4と並ぶのでcount_height_check_horizがいらなかった
  構造体で変数の枠消費を改善できた
  void関数で各処理を行なっていたものをint関数またはbool関数にすることによってflag変数で処理分岐をしないようにする実装ができた
