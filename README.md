# Wi-Fi Sensing Through Few-Shot Multi-Antenna Multi-Receiver CSI Learning

This repo contains code and dataset of the paper "ReWiS: Reliable Wi-Fi Sensing Through Few-Shot Multi-Antenna Multi-Receiver CSI Learning" 

Collected CSI dataset can be found at https://drive.google.com/drive/folders/1H-0GFOIHmHpHfdV-T5qv_diov_dCQxMS?usp=sharing
The folder `Formatted_data_frames` contains the cleaned, formatted and pre-processed data frames collected from 3 distinct environements, namely A1, A2 and A3. Data folders starts with `mXcY` where `X` indicates the number of monitors and Y is the number of antenna used for collecting the data. `trained_A1` is used for training the Few-shot model and `test_A2` and `test_A3` are used for testing. Each folder contains data for 4 activities, i.e., standing, walking, jumping and empty room.\
The folder `Raw_pcap` contains raw `.pcap` collected CSI data. 




1) Embedding training file
2) 1 monitors with trained embedding
3) 3 monitors with trained emeddings
