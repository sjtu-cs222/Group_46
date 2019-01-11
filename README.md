## Classification of Academic Topics Based on LDA
Group 46
516030910536 徐飞翔
516030910520 曹恒魁

The folder "pre" contains code for processing of Chinese text.

The folder "HMM" contains code for discovering new words automatically based on HMM.

The folder "sLDA" contains code for training and testing.
Type "make" in a shell. (Make sure the GSL is installed!)
To estimate the model, type "slda [est] [data] [label] [settings] [alpha] [k] [seeded/random/model_path] [directory]".
To perform inference on a different set of data (in the same format as for estimation), execute "slda [inf] [data] [label] [settings] [model] [directory]"

The final report is also attached.