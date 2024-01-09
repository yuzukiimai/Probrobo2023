# Probrobotics2023

## 概要
単純なグリッドワールドを用いて，Q学習により最適な方策の獲得を目指します．  
黄色のエージェント（ロボット）が緑色のゴールへ移動しながら学習します．  
各 episode ごとに必要とした step数（移動した回数）を可視化しました．

![robo](https://github.com/yuzukiimai/Probrobo2023/assets/91650008/7f05b11e-bd36-4399-9915-ecb97fa97990)


## 実行結果（100 episode）
・学習曲線（縦軸：step数，横軸：episode数）  
![curve](https://github.com/yuzukiimai/Probrobo2023/assets/91650008/248198ec-3b5a-473a-979e-0c986bfe48a5)  

・各episodeで必要とした step数をリスト化したもの  
![step](https://github.com/yuzukiimai/Probrobo2023/assets/91650008/f6a12b22-e208-4387-a409-76a7171c11e0)  

結果的に，30 episode付近で最適な方策を獲得できた．  
また，プロットした学習曲線から episodeが増えると，ゴールへ行くまでに必要とした step数が減少する様子を確認できた．  



