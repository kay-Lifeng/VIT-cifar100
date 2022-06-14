# Vision Transformer

## Getting Started

- Clone the repository

### Prerequisites

- Tensorflow 2.2.0+
- Tensorflow_addons
- Python 3.6+
- Keras 2.3.0
- PIL
- numpy

```python
pip install -r requirements.txt
```

## Running
### Training 
    ```
    python train.py
    ```
## Usage
### Training
```
usage: train.py [-h] [--logdir LOGDIR] [--image-size IMAGE_SIZE]
                [--patch-size PATCH_SIZE] [--num-layers NUM_LAYERS]
                [--d-model D_MODEL] [--num-heads NUM_HEADS]
                [--mlp-dim MLP_DIM] [--lr LR] [--weight-decay WEIGHT_DECAY]
                [--batch-size BATCH_SIZE] [--epochs EPOCHS]
```

```
optional arguments: -h, --help                show this help message and exit
                    --log_dir                 folder to save weights
                    --image_size              size of input image
                    --patch_size              size of patch to encode
                    --num-layers              number of transformer
                    --d-model                 embedding dimension
                    --mlp-dim                 hidden layer dimension
                    --lr                      learning rate
                    --weight-decay            weight decay
                    --batch-size              batch size
                    --epochs                  epochs
```


