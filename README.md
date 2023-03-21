## チェック済み
+ ### DGRec: Graph Neural Network for Recommendation with Diversified Embedding Generation
  - [[paper]](https://arxiv.org/abs/2211.10486)
  
+ ### Self-supervised Graph Learning for Recommendation
  - エッジをドロップアウトさせた2種類のグラフを学習に使用
  - [[paper]](https://arxiv.org/abs/2010.10783)
  
+ ### Are Graph Augmentations Necessary?: Simple Graph Contrastive Learning for Recommendation
  - エッジのドロップアウトの代わりに各層の埋め込みベクトルにノイズを加えてデータ拡張
  - [[paper]](https://arxiv.org/abs/2112.08679)
  
+ ### Contrastive learning for cold-start recommendation
  - [[paper]](https://arxiv.org/abs/2107.05315)
  
+ ### Contrastive Co-training for Diversified Recommendation
  - 普通のグラフと対照学習用のグラフで共同学習
  - 対照学習に用いるアイテムを相互作用数の逆数やカテゴリ数の逆数の比率でサンプリング
  - [[paper]](https://www.amazon.science/publications/contrastive-so-training-for-diversified-recommendation)
  
+ ### Investigating Accuracy-Novelty Performance for Graph-based Collaborative Filtering
  - 正規化係数の値を変えることでより高次の要素を取り込んだ埋め込みベクトルを得る
  - [[paper]](https://arxiv.org/abs/2204.12326)
  
+ ### Invariant Collaborative Filtering to Popularity Distribution Shift
  - 推薦の要因を人気による要因とアイテムそのものによる要因に分割
  - [[paper]](https://arxiv.org/abs/2302.05328)
  
+ ### Incorporating Bias-aware Margins into Contrastive Loss for Collaborative Filtering
  - [[paper]](https://arxiv.org/abs/2210.11054)

+ ### Learning to Denoise Unreliable Interactions for Graph Collaborative Filtering
  - 1回畳み込んだときのユーザとアイテムのスコアが低い場合ノイズとしてエッジを削除
  - 多様性を維持するためにユーザが未観測のアイテムとのエッジをランダム(?)で追加
  - [[paper]](https://dl.acm.org/doi/abs/10.1145/3477495.3531889) 

## チェック予定

+ ### Towards Robust Neural Graph Collaborative Filtering via Structure Denoising and Embedding Perturbation
  - 埋め込みベクトルにノイズを与える際に自分以外の埋め込みベクトルを使用(?)
  - [[paper]](https://dl.acm.org/doi/10.1145/3568396)

+ ### Countering Popularity Bias by Regularizing Score Differences
  - [[paper]](https://dl.acm.org/doi/abs/10.1145/3523227.3546757)

+ ### LightGCL: Simple Yet Effective Graph Contrastive Learning for Recommendation
  - [[paper]](https://arxiv.org/abs/2302.08191)
