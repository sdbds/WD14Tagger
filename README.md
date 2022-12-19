
# WD14Tagger

Automatically tag images with booru tags.



## Installation

```bash
  git clone https://github.com/KutsuyaYuki/WD14Tagger
  cd WD14Tagger
  conda env create -f environment.yaml
  conda activate wd14tagger
  pip install -r requirements.txt
```
    
## Usage/Examples

```bash
  python tag_images_by_wd14_tagger.py \
  input \
  --batch_size 4 \
  --caption_extension .txt
```

Change input to the folder where your images are located.

