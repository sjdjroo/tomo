# tomo
从稀疏点云到密集点云
| 类别      | 论文                                                                                                                  | 下载 / 阅读链接                                               | 代码                    |
| ------- | ------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- | --------------------- |
| 点云上采样   | **PU-Net: Point Cloud Upsampling Network, CVPR 2018**                                                               | PDF：([CVF开放获取][1]) / arXiv：([arXiv][2])                 | GitHub：([GitHub][3])  |
| 点云上采样   | **PU-GAN: A Point Cloud Upsampling Adversarial Network, ICCV 2019**                                                 | arXiv：([arXiv][4]) / PDF：([斯坦福大学计算机图形学][5])             | GitHub：([GitHub][6])  |
| 点云上采样   | **PUGeo-Net: A Geometry-centric Network for 3D Point Cloud Upsampling, ECCV 2020**                                  | arXiv：([arXiv][7]) / ECVA PDF：([欧洲计算机视觉协会][8])          | —                     |
| 点云上采样   | **PU-GCN: Point Cloud Upsampling Using Graph Convolutional Networks, CVPR 2021**                                    | CVF PDF：([CVF开放获取][9]) / arXiv：([arXiv][10])            | GitHub：([GitHub][11]) |
| 点云上采样   | **PU-Transformer: Point Cloud Upsampling Transformer, ACCV 2022**                                                   | arXiv：([arXiv][12]) / CVF PDF：([CVF开放获取][13])           | GitHub：([GitHub][14]) |
| 任意倍率上采样 | **Grad-PU: Arbitrary-Scale Point Cloud Upsampling via Gradient Descent with Learned Distance Functions, CVPR 2023** | arXiv：([arXiv][15]) / CVF PDF：([CVF开放获取][16])           | GitHub：([GitHub][17]) |
| 点云补全    | **PCN: Point Completion Network, 3DV 2018**                                                                         | arXiv：([arXiv][18])                                     | GitHub：([GitHub][19]) |
| 点云补全    | **PoinTr: Diverse Point Cloud Completion with Geometry-Aware Transformers, ICCV 2021**                              | arXiv：([arXiv][20]) / CVF PDF：([CVF开放获取][21])           | GitHub：([GitHub][22]) |
| 点云补全    | **SnowflakeNet: Point Cloud Completion by Snowflake Point Deconvolution with Skip-Transformer, ICCV 2021**          | arXiv：([arXiv][23]) / CVF PDF：([CVF开放获取][24])           | GitHub：([GitHub][25]) |
| 隐式表面重建  | **Points2Surf: Learning Implicit Surfaces from Point Cloud Patches, ECCV 2020**                                     | arXiv：([arXiv][26]) / ECVA PDF：([欧洲计算机视觉协会][27])        | GitHub：([GitHub][28]) |
| 隐式表面重建  | **POCO: Point Convolution for Surface Reconstruction, CVPR 2022**                                                   | arXiv：([arXiv][29]) / CVF PDF：([CVF开放获取][30])           | GitHub：([GitHub][31]) |
| 隐式表面重建  | **ALTO: Alternating Latent Topologies for Implicit 3D Reconstruction, CVPR 2023**                                   | arXiv：([arXiv][32]) / 项目页：([Visual Machines Group][33]) | —                     |

[1]: https://openaccess.thecvf.com/content_cvpr_2018/papers/Yu_PU-Net_Point_Cloud_CVPR_2018_paper.pdf?utm_source=chatgpt.com "PU-Net: Point Cloud Upsampling Network"
[2]: https://arxiv.org/abs/1801.06761?utm_source=chatgpt.com "PU-Net: Point Cloud Upsampling Network"
[3]: https://github.com/yulequan/PU-Net?utm_source=chatgpt.com "PU-Net: Point Cloud Upsampling Network"
[4]: https://arxiv.org/abs/1907.10844?utm_source=chatgpt.com "PU-GAN: a Point Cloud Upsampling Adversarial Network"
[5]: https://graphics.stanford.edu/courses/cs348n-22-winter/PapersReferenced/Li_PU-GAN_A_Point_Cloud_Upsampling_Adversarial_Network_ICCV_2019_paper.pdf?utm_source=chatgpt.com "PU-GAN: A Point Cloud Upsampling Adversarial Network"
[6]: https://github.com/liruihui/PU-GAN?utm_source=chatgpt.com "PU-GAN: a Point Cloud Upsampling Adversarial Network"
[7]: https://arxiv.org/abs/2002.10277?utm_source=chatgpt.com "PUGeo-Net: A Geometry-centric Network for 3D Point Cloud Upsampling"
[8]: https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123640732.pdf?utm_source=chatgpt.com "A Geometry-centric Network for 3D Point Cloud Upsampling"
[9]: https://openaccess.thecvf.com/content/CVPR2021/papers/Qian_PU-GCN_Point_Cloud_Upsampling_Using_Graph_Convolutional_Networks_CVPR_2021_paper.pdf?utm_source=chatgpt.com "PU-GCN: Point Cloud Upsampling Using Graph ..."
[10]: https://arxiv.org/abs/1912.03264?utm_source=chatgpt.com "PU-GCN: Point Cloud Upsampling using Graph Convolutional Networks"
[11]: https://github.com/guochengqian/PU-GCN?utm_source=chatgpt.com "[CVPR'21] PU-GCN: Point Cloud Upsampling using Graph ..."
[12]: https://arxiv.org/abs/2111.12242?utm_source=chatgpt.com "[2111.12242] PU-Transformer: Point Cloud Upsampling ..."
[13]: https://openaccess.thecvf.com/content/ACCV2022/papers/Qiu_PU-Transformer_Point_Cloud_Upsampling_Transformer_ACCV_2022_paper.pdf?utm_source=chatgpt.com "PU-Transformer: Point Cloud Upsampling Transformer"
[14]: https://github.com/ShiQiu0419/PU-Transformer?utm_source=chatgpt.com "ShiQiu0419/PU-Transformer"
[15]: https://arxiv.org/abs/2304.11846?utm_source=chatgpt.com "Grad-PU: Arbitrary-Scale Point Cloud Upsampling via Gradient Descent with Learned Distance Functions"
[16]: https://openaccess.thecvf.com/content/CVPR2023/papers/He_Grad-PU_Arbitrary-Scale_Point_Cloud_Upsampling_via_Gradient_Descent_With_Learned_CVPR_2023_paper.pdf?utm_source=chatgpt.com "Grad-PU: Arbitrary-Scale Point Cloud Upsampling via ..."
[17]: https://github.com/yunhe20/Grad-PU?utm_source=chatgpt.com "yunhe20/Grad-PU: This is the official PyTorch ..."
[18]: https://arxiv.org/abs/1808.00671?utm_source=chatgpt.com "[1808.00671] PCN: Point Completion Network"
[19]: https://github.com/wentaoyuan/pcn?utm_source=chatgpt.com "Code for PCN: Point Completion Network in 3DV'18 (Oral) · ..."
[20]: https://arxiv.org/abs/2108.08839?utm_source=chatgpt.com "PoinTr: Diverse Point Cloud Completion with Geometry-Aware Transformers"
[21]: https://openaccess.thecvf.com/content/ICCV2021/papers/Yu_PoinTr_Diverse_Point_Cloud_Completion_With_Geometry-Aware_Transformers_ICCV_2021_paper.pdf?utm_source=chatgpt.com "PoinTr: Diverse Point Cloud Completion With Geometry- ..."
[22]: https://github.com/yuxumin/PoinTr?utm_source=chatgpt.com "PoinTr: Diverse Point Cloud Completion with Geometry ..."
[23]: https://arxiv.org/abs/2108.04444?utm_source=chatgpt.com "SnowflakeNet: Point Cloud Completion by Snowflake Point Deconvolution with Skip-Transformer"
[24]: https://openaccess.thecvf.com/content/ICCV2021/papers/Xiang_SnowflakeNet_Point_Cloud_Completion_by_Snowflake_Point_Deconvolution_With_Skip-Transformer_ICCV_2021_paper.pdf?utm_source=chatgpt.com "SnowflakeNet: Point Cloud Completion by Snowflake ..."
[25]: https://github.com/AllenXiangX/SnowflakeNet?utm_source=chatgpt.com "AllenXiangX/SnowflakeNet: (TPAMI 2023) Snowflake Point ..."
[26]: https://arxiv.org/abs/2007.10453?utm_source=chatgpt.com "Points2Surf: Learning Implicit Surfaces from Point Cloud Patches"
[27]: https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123500103.pdf?utm_source=chatgpt.com "Points2Surf"
[28]: https://github.com/ErlerPhilipp/points2surf?utm_source=chatgpt.com "Points2Surf: Learning Implicit Surfaces from Point Clouds ..."
[29]: https://arxiv.org/abs/2201.01831?utm_source=chatgpt.com "POCO: Point Convolution for Surface Reconstruction"
[30]: https://openaccess.thecvf.com/content/CVPR2022/papers/Boulch_POCO_Point_Convolution_for_Surface_Reconstruction_CVPR_2022_paper.pdf?utm_source=chatgpt.com "POCO: Point Convolution for Surface Reconstruction"
[31]: https://github.com/valeoai/POCO?utm_source=chatgpt.com "[CVPR 2022] POCO: Point Convolution for Surface ..."
[32]: https://arxiv.org/abs/2212.04096?utm_source=chatgpt.com "ALTO: Alternating Latent Topologies for Implicit 3D Reconstruction"
[33]: https://visual.ee.ucla.edu/alto.htm/?utm_source=chatgpt.com "ALTO: Alternating Latent Topologies for Implicit 3D ..."
