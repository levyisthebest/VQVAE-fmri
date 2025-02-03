




## :hammer_and_wrench: Requirements

```python3
conda create -n ECHOPulse python==3.8
conda activate ECHOPulse
pip install -r requirements.txt
```

## :gear: Train & Test

### Training video tokenization model
```bash
python step1_train.py
```
### Training video generation model
```bash
python step2_train.py
```
### Pretrained model weights
[**Model Weights**](https://huggingface.co/datasets/Levi980623/ECHOTest/tree/main) should be downloaded and put into the Model_weights folder. The ECG Foundation Model used in this repo is called [**ST-MEM**](https://github.com/bakqui/ST-MEM/tree/main).

### Inference
```python3
echo_inference.ipynb
```
### Citation
If you use the code, please cite the following paper:
```
@article{li2024echopulse,
  title={ECHOPulse: ECG controlled echocardio-grams video generation},
  author={Li, Yiwei and Kim, Sekeun and Wu, Zihao and Jiang, Hanqi and Pan, Yi and Jin, Pengfei and Song, Sifan and Shi, Yucheng and Yang, Tianze and Liu, Tianming and others},
  journal={arXiv preprint arXiv:2410.03143},
  year={2024}
}
```
