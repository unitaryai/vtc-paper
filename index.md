VTC is a large-scale multimodal dataset containing video-caption pairs alongside comments that can be used for multimodal representation learning.

<p align="center">
<img src="https://raw.githubusercontent.com/unitaryai/VTC/main/vtc_fig.png">
</p>

### Dataset Curation

This dataset is a sample of a larger, unfiltered version of the original dataset that we have collected. From the initial version, we handpicked a list of ”safe” subreddits and removed posts if: 1) they had the ”NSFW” or ”over 18” tags; 2) the videos contained faces or the captions contained toxic or offensive text.

We are only publicly releasing urls such that if a user decides to remove a post, the link to the post will become invalid. This dataset should not be used for tasks that might disclose the identity of the users or directly or indirectly harm them.

### Download

The public csv containing post urls and comment ids can be downloaded from [here](https://github.com/unitaryai/VTC/releases/download/v0.1.0-alpha/VTC_v1.0_public.csv.tar.gz). To download the media please see our code [here](https://github.com/unitaryai/VTC-dataset).

### Code & Checkpoints

Code to reproduce our experiments and saved model checkpoints can be found [here](https://github.com/unitaryai/VTC).


### Citation

```text
@inproceedings{hanu2022vtc,
    title={VTC: Improving Video-Text Retrieval with User Comments},
    author={Laura Hanu and James Thewlis and Yuki M. Asano and Christian Rupprecht},
    booktitle={ECCV},
    year={2022}
}
```

### Contact

For questions regarding the dataset or the paper please email laura@unitary.ai.
