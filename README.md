# Gaussian Mixture Model with Expectatoin Maximization Algorithm

please see a implementation in GMM.ipynb


|model| num of gauss dist. | conv type | params|end epoch \(thresh=1e-3)|log_likelihood|BIC |
|:---:|:---:    |:---:     |:---:  |:---:                 |:---:         |:---:|   
|K1_diag0| 1 | full | 5|2|-7699.809|15435.840|
|K1_diag1| 1 | diag | 4|2|-9274.189|18577.356|
|K2_diag0| 2 | full | 11|15|-6152.370|12377.182|
|K2_diag1| 2 | diag | 9|7|-6884.938|13827.830|
|**K3_diag0**| 3 | full | 17|24|-5451.755|**11012.173**|
|K3_diag1| 3 | diag | 14|9|-5702.959|11492.849|
|K4_diag0| 4 | full | 23|29|-5448.348|11041.580|
|K4_diag1| 4 | diag | 19|29|-5700.893|11517.694|
|K4_diag0| 5 | full | 29|29|-5446.084|11073.273|
|K5_diag1| 5 | diag | 24|29|-5699.974|11544.833|

## BIC to K size
<img src='result/BIC.png'>

## K1_diag0
<img src='result/result_K1_diag0.png' width=50%>
<img src='gif/gif_K1_diag0_dist.gif' width=50%>
<img src='gif/gif_K1_diag0_loss.gif' width=50%>

## K1_diag1
<img src='result/result_K1_diag1.png' width=50%>
<img src='gif/gif_K1_diag1_dist.gif' width=50%>
<img src='gif/gif_K1_diag1_loss.gif' width=50%>

## K2_diag0
<img src='result/result_K2_diag0.png' width=50%>
<img src='gif/gif_K2_diag0_dist.gif' width=50%>
<img src='gif/gif_K2_diag0_loss.gif' width=50%>

## K2_diag1
<img src='result/result_K2_diag1.png' width=50%>
<img src='gif/gif_K2_diag1_dist.gif' width=50%>
<img src='gif/gif_K2_diag1_loss.gif' width=50%>

## K3_diag0
<img src='result/result_K3_diag0.png' width=50%>
<img src='gif/gif_K3_diag0_dist.gif' width=50%>
<img src='gif/gif_K3_diag0_loss.gif' width=50%>

## K3_diag1
<img src='result/result_K3_diag1.png' width=50%>
<img src='gif/gif_K3_diag1_dist.gif' width=50%>
<img src='gif/gif_K3_diag1_loss.gif' width=50%>

## K4_diag0
<img src='result/result_K4_diag0.png' width=50%>
<img src='gif/gif_K4_diag0_dist.gif' width=50%>
<img src='gif/gif_K4_diag0_loss.gif' width=50%>

## K4_diag1
<img src='result/result_K4_diag1.png' width=50%>
<img src='gif/gif_K4_diag1_dist.gif' width=50%>
<img src='gif/gif_K4_diag1_loss.gif' width=50%>

## K5_diag0
<img src='result/result_K5_diag0.png' width=50%>
<img src='gif/gif_K5_diag0_dist.gif' width=50%>
<img src='gif/gif_K5_diag0_loss.gif' width=50%>

## K5_diag1
<img src='result/result_K5_diag1.png' width=50%>
<img src='gif/gif_K5_diag1_dist.gif' width=50%>
<img src='gif/gif_K5_diag1_loss.gif' width=50%>
