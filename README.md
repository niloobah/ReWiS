# Wi-Fi Sensing Through Few-Shot Multi-Antenna Multi-Receiver CSI Learning

This repo contains code and dataset of the paper "ReWiS: Reliable Wi-Fi Sensing Through Few-Shot Multi-Antenna Multi-Receiver CSI Learning" 


## Dataset
Collected CSI dataset can be found at https://drive.google.com/drive/folders/1H-0GFOIHmHpHfdV-T5qv_diov_dCQxMS?usp=sharing \
The folder `Formatted_data_frames` contains the cleaned, formatted and pre-processed data frames collected from 3 distinct environements, namely A1, A2 and A3. Data folders starts with `mXcY` where `X` indicates the number of monitors and Y is the number of antenna used for collecting the data. `trained_A1` is used for training the Few-shot model and `test_A2` and `test_A3` are used for testing. Each folder contains data for 4 activities, i.e., standing, walking, jumping and empty room.\
The folder `Raw_pcap` contains raw `.pcap` collected CSI data. 
## Code
For datasets with one monitor use `one_mon.py` and `one_mon_trained_embedding.py`.\
`one_mon_trained_embedding.py` utilizes a CNN for embedded training, while `one_mon.py` utilizes resnet 12 for embedding training.\

For datasets with three monitors use `three_mons.py` and `three_mon_trained_embedding.py`.\
`three_mon_trained_embedding.py` utilizes a CNN for embedded training, while `three_mons.py` utilizes resnet 12 for embedding training.\

## Usage
- Download the dataset in folder `Formatted_data_frames`
- Place datasets in folder `few_shot_datasets`
- Pick the propoer datafolder for training:  `m1c1_xxx` or `m1c4_xxx` for `one_mon_trained_embedding.py` and `m3c1_xxx` or `m3c4_xxx` for `three_mon_trained_embedding.py`.
- Pick the desired testing environment (either A2 or A3).




