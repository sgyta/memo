## チェック済み
+ ### DGRec: Graph Neural Network for Recommendation with Diversified Embedding Generation (WSDM 2023)
  - 類似度が最小になるように隣接ノードのアイテムをサンプリング，カテゴリ内のアイテム数が少ないアイテムが重要になるように重みづけ
  - [[paper]](https://arxiv.org/abs/2211.10486) [[code]](https://github.com/YangLiangwei/DGRec)

<br>

+ ### Self-supervised Graph Learning for Recommendation (SIGIR 2021)
  - 対照学習を用いた推薦システムのベースとなる論文
  - グラフに2種類の拡張を加えたそれぞれのユーザ同士・アイテム同士を比較
  - 拡張はノードドロップアウト、エッジドロップアウト、ランダムウォークの3種類
  - [[paper]](https://arxiv.org/abs/2010.10783) [[code]](https://github.com/wujcan/SGL-Torch)

<br>

+ ### Are Graph Augmentations Necessary?: Simple Graph Contrastive Learning for Recommendation (SIGIR 2022)
  - グラフの拡張の代わりに各層の埋め込みベクトルにノイズを加えてデータ拡張
  - [[paper]](https://arxiv.org/abs/2112.08679) [[code]](https://github.com/Coder-Yu/QRec)

<br>

+ ### Contrastive Co-training for Diversified Recommendation (IJCNN 2022)
  - 普通のグラフと対照学習用のグラフで共同学習
  - 対照学習に用いるアイテムを相互作用数の逆数やカテゴリ数の逆数の比率でサンプリング
  - [[paper]](https://www.amazon.science/publications/contrastive-so-training-for-diversified-recommendation)
  
<br>

+ ### Investigating Accuracy-Novelty Performance for Graph-based Collaborative Filtering (SIGIR 2022)
  - 正規化係数の値を変えることでより高次の要素を取り込んだ埋め込みベクトルを得る→新規性向上
  - [[paper]](https://arxiv.org/abs/2204.12326)
  
<br>
  
+ ### Invariant Collaborative Filtering to Popularity Distribution Shift (WWW 2023)
  - 推薦の要因を人気による要因とアイテムそのものによる要因に分割
  - [[paper]](https://arxiv.org/abs/2302.05328) [[code]](https://github.com/anzhang314/InvCF)

<br>

+ ### Incorporating Bias-aware Margins into Contrastive Loss for Collaborative Filtering (NeurIPS 2022)
  - インタラクション数のみを考慮した推薦でマージンを取る
  - [[paper]](https://arxiv.org/abs/2210.11054) [[code]](https://github.com/anzhang314/BC-Loss)

<br>

+ ### Learning to Denoise Unreliable Interactions for Graph Collaborative Filtering (SIGIR 2022)
  - 1回畳み込んだときのユーザとアイテムのスコアが低い場合ノイズとしてエッジを削除
  - 多様性を維持するためにユーザと未観測のアイテム間のエッジを追加
  - [[paper]](https://dl.acm.org/doi/abs/10.1145/3477495.3531889) [[code]](https://github.com/ChangxinTian/RGCF)

<br>

## チェック予定

+ ### Towards Robust Neural Graph Collaborative Filtering via Structure Denoising and Embedding Perturbation
  - 埋め込みベクトルにノイズを与える際に自分以外の埋め込みベクトルを使用(?)
  - [[paper]](https://dl.acm.org/doi/10.1145/3568396)

<br>

+ ### Countering Popularity Bias by Regularizing Score Differences (RecSys 2022)
  - [[paper]](https://dl.acm.org/doi/abs/10.1145/3523227.3546757) [[code]](https://github.com/stillpsy/popbias)


<br>

+ ### LightGCL: Simple Yet Effective Graph Contrastive Learning for Recommendation (ICLR 2023)
  - [[paper]](https://arxiv.org/abs/2302.08191) [[code]](https://github.com/HKUDS/LightGCL)