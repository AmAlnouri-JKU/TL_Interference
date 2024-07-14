# Detrimental Memories in Transfer Learning
This repository provides the necessary resources to reproduce the heatmaps presented in the paper "<a href="https://openreview.net/pdf?id=mALjVQZV8N">Detrimental Memories in Transfer Learning</a>". You will find links to download the finetuned models used to conduct the experiments discussed in the paper.

## Abstract
The source domain in transfer learning provides essential features that enable effective and data-efficient learning on the target task. Typically, the finetuning process does not explicitly account for how the knowledge about the source domain interacts with the target task. We demonstrate how that knowledge can interfere with the target task leading to negative transfer. Specifically, certain memories about the source domain can distract the finetuned model in certain inputs. We provide a method to analyze those memories in typical foundational models and to surface potential failure cases of those models. This analysis helps model developers explore remedies for those failure cases, such as expanding the training data or adapting the training objective.

## Requirements
- Python 3.7
- Jupyter Notebook
- PyTorch
- torchvision
- torchcam
- pillow
- Matplotlib

## Installation
To set up the environment, clone this repository and install the required dependencies:
```bash
git clone https://github.com/AmAlnouri-JKU/TL_Interference.git
cd TL_Interference
pip install -r requirements.txt
```

## Models
You can download the finetuned models from the following links:
- <a href="https://drive.google.com/drive/folders/1Re7E9SfjhdOwOmotyuEgtNgsF3vDmNep?usp=drive_link">ResNet-18</a>
- <a href="https://drive.google.com/drive/folders/1fE4pMbnPwNlPuazu15XG4_PHKPDqDuZ1?usp=drive_link">VGG-16</a>
- <a href="https://drive.google.com/drive/folders/1DUHRMiAaKxy3ElBFVIAMuyUV2sx3RaHk?usp=drive_link">GoogleNet</a>
- <a href="https://drive.google.com/drive/folders/15V6t2mj80CNIjz3lZrKP8CJOmfc8MdlE?usp=drive_link">ResNet-18 (Baseline)</a>
- <a href="https://drive.google.com/drive/folders/1nm9Ppeoi9aaLHGSEGxfyVpRsHmCtd_Dy?usp=drive_link">ResNet-18 (SimCLR)</a>

Please download the models and place them in the `models` directory.
