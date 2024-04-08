# InstanceDetection
object detection with transfer learning

# relevant info
- https://medium.com/@c_61011/transfer-learning-with-mask-r-cnn-f50cbbea3d29#4770
- https://www.robots.ox.ac.uk/~vgg/software/via/


# needed models
## segmentation
- semantic segmentation
- instance segmentation
- **panoptic segmentation**

# retraining the model
- transfer learning
- fine tuning

https://huggingface.co/docs/transformers/main/en/tasks/object_detection
- https://colab.research.google.com/github/huggingface/notebooks/blob/main/transformers_doc/en/tensorflow/object_detection.ipynb
- https://colab.research.google.com/github/huggingface/notebooks/blob/main/transformers_doc/en/pytorch/object_detection.ipynb


# create coco style dataset
import convert as via2coco

https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/YOLOS/Fine_tuning_YOLOS_for_object_detection_on_custom_dataset_(balloon).ipynb#scrollTo=VkAzYMYb0ED7
https://github.com/woctezuma/VIA2COCO
https://github.com/codingwolfman/VIA2COCO

https://patrickwasp.com/create-your-own-coco-style-dataset/
https://github.com/waspinator/pycococreator/




# using GPU in devcontainer
https://stackoverflow.com/questions/72129213/using-gpu-in-vs-code-container

1. install cuda https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html
2. add `"runArgs": [
    "--gpus",
    "all"
]` to devcontainer.json


