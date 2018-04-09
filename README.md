# Detectron

My detectron: 
1. add boundary

RUN:
CUDA_VISIBLE_DEVICES=0,3,5,6 python2 tools/train_net.py  --multi-gpu-testing   --cfg configs/mymodel/e2e_mask_rcnn_R-50-FPN_4GPU_1x_minitrain.yaml
