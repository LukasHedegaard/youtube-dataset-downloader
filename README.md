# YouTube Dataset Downloader
Download utility for datasets from YouTube

## Setup
```bash
conda env create --file environment.yml
conda activate youtube-downloader
```

## Usage examples
```bash
python download.py \
--input-csv ~/kinetics400/splits/train.csv \
--output-dir ~/kinetics400/data/train/ \
--num-jobs 1 \
```

```bash
python download.py \
--input-json ~/YouTube-Birds/test_list.json \
--label2name ~/YouTube-Birds/label2name.json \
--output-dir ~/YouTube-Birds/test \
--num-jobs 2
```

Currently tested on 
- [Kinetics400](https://deepmind.com/research/open-source/kinetics)
- [Kinetics600](https://deepmind.com/research/open-source/kinetics)
- [Kinetics700](https://deepmind.com/research/open-source/kinetics)
- [YouTube-Birds](https://www.cs.umd.edu/~chenzhu/fgvc/)
- [YouTube-Cars](https://www.cs.umd.edu/~chenzhu/fgvc/)

