# efficientnet_lite

The original repo lacks inference example for trained tflite models, 
therefore this a benchmark summary on tflite-int8  downloaded from : [here](https://github.com/tensorflow/tpu/tree/master/models/official/efficientnet/lite)

[1] Mingxing Tan and Quoc V. Le.  EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks. ICML 2019.
   Arxiv link: https://arxiv.org/abs/1905.11946.

## Quick Run: 

python eval_ckpt_main.py --runmode=imagenet_lite --model_name=efficientnet-lite0 --imagenet_eval_glob=/Volumes/wd/ILSVRC2012_img_val/ILSVRC2012*.JPEG  --imagenet_eval_label=ground_truth_corrected.txt --num_images=100 --tflite_path=efficientnet-lite0/efficientnet-lite0-int8.tflite


[notebooks for results]: (https://github.com/forecastorm/efficientnet_lite/blob/main/efficientnet0_int8.ipynb)

