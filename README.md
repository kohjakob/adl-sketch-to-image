## Applied Deep Learning
## Jakob Kohlhas - 12208214

---

- Project topic: Image Generation
- Project type: Bring your own method

---

I want to explore **conditional image generation** with a focus on **(freehand) sketches** as the conditional input modality. For the project i plan to **reimplement MaskSketch** [1].
MaskSketch leverages the intermediate self-attention maps of a pretrained MaskGIT [2] backbone encoding spatial and structural information to guide the image generation process. MaskSketch does not need sketch-photo paired data for training.
I plan on exploring and experimenting with different structural distance measures and other hyperparameters.

### References

1. [Bashkirova, Dina, et al. "*MaskSketch: Unpaired Structure-guided Masked Image Generation*"](https://arxiv.org/pdf/2302.05496v1) Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2023.
2. [Chang, Huiwen, et al. "*MaskGIT: Masked Generative Image Transformer*"](https://arxiv.org/pdf/2202.04200) Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2022.
3. [Tumanyan, Narek, et al. "*Splicing ViT Features for Semantic Appearance Transfer*"](https://arxiv.org/abs/2201.00424) Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2022.


### Dataset

For evaluation [ImageNet-Sketch](https://www.kaggle.com/datasets/wanghaohan/imagenetsketch) and [Pseudosketches](https://cusuh.github.io/CoGS/) can be used.

### Work Breakdown

| Task                                      | Estimated Time | Due to |
|-------------------------------------------|----------------|--------|
| **Research and Planning**                 | 14 days        | 05.11  |
| - Understand MaskSketch and MaskGIT       |                |              |
| - Review related papers and techniques    |                |              |
| **Reimplementation of MaskSketch**                      | 14 days        | 19.11  |
| **Exploration and Experimentation**       | 28 days        | 17.11 (Submission 2)|
| - Explore sturctural distance measures    |                |              |
| - Explore further adjustments             |                |              |
| **Evaluation**                            | 7 days         | 24.11  |
| - Run comparative experiments to evaluate made   adjustments                                 |                |              |
| **Reserved time to distribute freely**                         | 28 days        | 14.01  |
| **Final presentation**                    | 7 days         | 21.01  (Submission 3) |
| - Fine-tune MaskGIT/MaskSketch models     |                |              |
| - Experiment with hyperparameters         |                |              |
