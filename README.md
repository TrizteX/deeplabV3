# DeeplabV3

This is a PyTorch 1.6.0 implementation of Deeplabv3 running on resnet 101 backbone. 
The pre-trained model has been trained on a subset of COCO train2017, on the 20 categories that are present in the Pascal VOC dataset.

**Requirements:**
1. Python 3.6+ 
2. Pytorch 1.5.0+
3. Torchvision 0.6.0+
4. Pillow 7.2.0+
5. Matplotlib 3.2.2+

**Usage**

Filename parameter can be changed in main.py

Images must be in .jpg format and atleast 224x224 pixels.

```python
from main import deep
deep()
```

**Output**
The output segmentated image is saved as img.jpg in the current working directory.
