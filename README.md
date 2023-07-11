# grad_cam-pytorch-custom
cnn model interpretablity

clone the gradcam repo
```
git clone https://github.com/jacobgil/pytorch-grad-cam.git
```
replace old cam.py with my cam.py ,do changes inside cam.py & run the code

Usage: ```python cam.py --image-path <path_to_image> --method <method> --output-dir <output directory> ```

To use with CUDA: ```python cam.py --image-path <path_to_image> --use-cuda  --output-dir <output directory> ```
