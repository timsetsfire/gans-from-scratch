#  Generative Adversarial Networks from Scratch

## Requirements

We'll use my [scala-miniflow](https://github.com/timsetsfire/scala-miniflow) project to build and train neural networks.

## Setup

1. Download the free [Anaconda Distribution](https://www.anaconda.com/download)
2. Clone this repository
3. Clone [scala-miniflow](https://github.com/timsetsfire/scala-miniflow)
4. Install [beakerx](http://beakerx.com/documentation#tutorials-and-examples)

```
conda create -y -n beakerx 'python>=3'
source activate beakerx
conda config --env --add pinned_packages 'openjdk>8.0.121'
conda install -y -c conda-forge ipywidgets beakerx=1.0.0
```

## Using notebook

`source activate beakerx` on linux / mac or `activate beakerx` on windows.  
`jupyter notebook`
In kernels - select Scala.
