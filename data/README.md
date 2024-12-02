The SpeechOcean762 dataset used in this paper can be downloaded from [this link](https://www.openslr.org/101).

If you want to skip Kaldi GOP recipe and data preprocessing, you can use our intermediate files. This is useful if you do not want to change the acoustic model and save some time.

Download from this [onedrive link](https://iiitaphyd-my.sharepoint.com/:u:/g/personal/vansh_garg_research_iiit_ac_in/EegpOfln5ThFszDqLYxuvs4BY8bLjWFrceswH6qdmuS7Bg?e=NIwPpn)

```
data
│   README.md
└───raw_kaldi_gop
│   │   librispeech
│   │   │   tr_feats.csv
│   │   │   tr_keys_phn.csv
│   │   │   tr_keys_word.csv
│   │   │   tr_feats.csv
│   │   │   ... (10 files in total)
│   
└───seq_data_librispeech
    │   tr_feat.npy
    │   tr_label_phn.npy
    │   tr_label_word.npy
    │   tr_label_utt.npy
    │   ... (8 files in toal)
└───seq_data_paiia
    │   tr_feat.npy
    │   tr_label_phn.npy
    │   tr_label_word.npy
    │   tr_label_utt.npy
    │   ... (8 files in toal)
└───seq_data_paiib
    │   tr_feat.npy
    │   tr_label_phn.npy
    │   tr_label_word.npy
    │   tr_label_utt.npy
    │   ... (8 files in toal)
```