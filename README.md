# SD-1.5 Low-Level Optimization Techniques

This notebook was created in the context of the seminar "Generative AI with Diffusion Models" at the Technical University of Munich.

It documents some benchmarks I have done to evaluate the performance improvements gained from lowering precision, using FlashAttention, channel-last memory format, `torch.compile()` and other techniques.

The benchmark was conducted on Google Colab using a T4 GPU.
The resulting statistics and techniques were presented by me during the seminar.
