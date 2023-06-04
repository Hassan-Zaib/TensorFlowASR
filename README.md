# Getting started with TensorFlow ASR


## Create conda env

```conda create —name asr_25 python=3.8.5
conda activate asr_25
pip install -r requirements.txt
python scripts/create_librispeech_trans.py --dir /mydata/hassan/data/LibriSpeech/dev-clean/ /mydata/hassan/data/LibriSpeech/dev-clean/transcript.tsv # Optional
python scripts/create_librispeech_trans.py --dir /mydata/hassan/data/LibriSpeech/train-clean-100/ /mydata/hassan/data/LibriSpeech/train-clean-100/transcript.tsv # Optional
python scripts/create_librispeech_trans.py --dir /mydata/hassan/data/LibriSpeech/test-clean/ /mydata/hassan/data/LibriSpeech/test-clean/transcript.tsv
Python examples/conformer/test.py —saved /path/to/latest.h5
```


