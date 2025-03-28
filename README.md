# Deep Learning Notebook

This repository presents an annotated version of the paper in the form of a line-by-line implementation. It reorders and deletes some sections from the original paper and adds comments throughout. Each document itself is a working notebook, and should be a completely usable implementation.

Inspired by [The Annotated Transformer](https://nlp.seas.harvard.edu/annotated-transformer/), I create this repository to record my attempts to implement the method in the paper. I try my best to implement the method as straightforwardly as possible to maximize clarity and ease of understanding. References are listed in each notebook. I strongly recommend you to read the original paper and the official implementation.

## Paper Implementations

* [ConSinGAN](ConSinGAN/ConSinGAN.ipynb)
* [CycleGAN](CycleGAN/CycleGAN.ipynb)
* [SinGAN](SinGAN/SinGAN.ipynb)
* [Swin Transformer](SwinTransformer/swin_transformer.ipynb)
* [Swin Transformer v2](SwinTransformer_v2/swin_transformer.ipynb)
* [Transformer](Transformer/transformer.ipynb)
* [U2Fusion](U2Fusion/U2Fusion.ipynb)
* [Vision Transformer](VisionTransformer/vision_transformer.ipynb)

## Data

You need to create a folder named `data` in the root directory and place the downloaded datasets inside the `data` directory.

Below is an example of how the `data` directory should be structured:

```
data/
├── Lytro/
│   ├── A/
│   │   ├── image1.jpg
│   │   ├── image2.jpg
│   │   ├── ...
│   └── B/
│       ├── image3.jpg
│       ├── image4.jpg
│       ├── ...
├── monet2photo/
│   ├── trainA/
│   │   ├── image5.jpg
│   │   ├── ...
│   ├── trainB/
│   │   ├── image6.jpg
│   │   ├── ...
```

Ensure that the datasets are organized according to the requirements of each specific implementation.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.