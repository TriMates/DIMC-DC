# The source code is the demo of for the paper: Deep Incomplete Multi-view Clustering with Dual Consistencies via IB. The whole code will be public after the acceptance.

## The usage of DIMC-DC model

``` 
--dataset wikipedia --data_dir data/wikipedia --pretrain load_ae
--img_cptpath cpt/wikipedia_img_pretrain_checkpt_252.pkl
--txt_cptpath cpt/wikipedia_txt_pretrain_checkpt_247.pkl
--lr_g 1e-4 --lr_d 5e-5 --lr_ae 5e-4 --gan_type wasserstein --n_epochs
500 --weight_decay 0 --lamda3 0.5 --lamda1 1 --cpt_dir cpt --seed 2018
```
