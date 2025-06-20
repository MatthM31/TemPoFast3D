# Official Implementation for TemPoFast3D (CVPR 2025)
> **Link to the Past: Temporal Propagation for Fast 3D Human Reconstruction from Monocular Video** [[Paper](https://arxiv.org/abs/2505.07333)] [[Website](https://matthm31.github.io/TemPoFast3D/)]

# TODO

- [ ] Release code
- [x] Release paper


# Introduction
Fast 3D clothed human reconstruction from monocular video remains a significant challenge in computer vision, particularly in balancing computational efficiency with reconstruction quality. Current approaches are either focused on static image reconstruction but too computationally intensive, or achieve high quality through per-video optimization that requires minutes to hours of processing, making them unsuitable for real-time applications. To this end, we present TemPoFast3D, a novel method that leverages temporal coherency of human appearance to reduce redundant computation while maintaining reconstruction quality. Our approach is a "plug-and play" solution that uniquely transforms pixel-aligned reconstruction networks to handle continuous video streams by maintaining and refining a canonical appearance representation through efficient coordinate mapping. Extensive experiments demonstrate that TemPoFast3D matches or exceeds state-of-the-art methods across standard metrics while providing high-quality textured reconstruction across diverse pose and appearance, with a maximum speed of 12 FPS.