# TAUE: Training-free Noise Transplant and Cultivation Diffusion Model

[![arXiv](https://img.shields.io/badge/arXiv-2511.02580-b31b1b.svg)](https://arxiv.org/abs/2511.02580)
[![Huggingface Diffusers](https://img.shields.io/badge/🤗_Huggingface-Diffusers-yellow.svg)](https://huggingface.co/docs/diffusers/main/en/index)
[![Project Page](https://img.shields.io/badge/Project_Page-TAUE-green.svg)](https://iyatomilab.github.io/TAUE/)

Daichi Nagai*, [Ryugo Morita](https://ryugo417.github.io/)*, [Shunsuke Kitada](https://shunk031.me/), [Hitoshi Iyatomi](https://iyatomi-lab.info/english-top)

## Abstract

Despite the remarkable success of text-to-image diffusion models, their output of a single, flattened image remains a critical bottleneck for professional applications requiring layer-wise control. Existing solutions either rely on fine-tuning with large, inaccessible datasets or are training-free yet limited to generating isolated foreground elements, failing to produce a complete and coherent scene. To address this, we introduce the Training-free Noise Transplantation and Cultivation Diffusion Model (TAUE), a novel framework for zero-shot, layer-wise image generation. Our core technique, Noise Transplantation and Cultivation (NTC), extracts intermediate latent representations from both foreground and composite generation processes, transplanting them into the initial noise for subsequent layers. This ensures semantic and structural coherence across foreground, background, and composite layers, enabling consistent, multi-layered outputs without requiring fine-tuning or auxiliary datasets. Extensive experiments show that our training-free method achieves performance comparable to fine-tuned methods, enhancing layer-wise consistency while maintaining high image quality and fidelity. TAUE not only eliminates costly training and dataset requirements but also unlocks novel downstream applications, such as complex compositional editing, paving the way for more accessible and controllable generative workflows.

## LICENSE

Apache License 2.0
