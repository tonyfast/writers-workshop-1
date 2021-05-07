# Hello fellow human :wave:

I'm a scientific software engineer at [Quansight](https://www.quansight.com/) working on [PyTorch](https://pytorch.org). I'm very active in the [`torchvision`](https://github.com/pytorch/vision) library and maintain the `torchvision.datasets` module there.

Outside of my work I have two major areas of interest:

1. :art: **Neural Style Transfer**:
    During my research towards a PhD, I fell in love with [Neural Style Transfer](https://en.wikipedia.org/wiki/Neural_Style_Transfer). I realized pretty soon that the available tooling is insufficient. Out of frustration with all the existing solutions, I wrote my own library for Neural Style Transfer based on PyTorch: [`pystiche`](https://github.com/pmeier/pystiche).
2. :computer: **Developer Experience**:
    Having worked on PyTorch and having written a library based on PyTorch I realized there are a few pain points for me. So I started some projects to make my life and hopefully everyone elses easier:
    - [`pytest-pytorch`](https://github.com/Quansight/pytest-pytorch): PyTorch's test suite is only partially compatible with [`pytest`](https://docs.pytest.org/). This is a small plugin to make them play ball.
    - [`light-the-torch`](https://github.com/pmeier/light-the-torch): Installing pure Python libraries that depend on PyTorch is quite frustrating, since `pip` has no option to detect the available computation backends (CUDA, ROCm) and install the correct PyTorch binary. This is a small drop-in replacement for `pip install` to make it happen.
    - [`pytorch-pip-shim`](https://github.com/pmeier/pytorch-pip-shim): Next evolutional step after `light-the-torch`: invasive, but with a better UX. Install once and never worry again.

- :speech_balloon: Ask me about: Python, PyTorch, Neural Style Transfer
- :mailbox: How to reach me: Open an [issue](https://github.com/pmeier/pmeier/issues) in my personal repository.
- :smile: Pronouns: he/him/his
