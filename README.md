project-st-19-01-PredictivePollution
==============================
Project to classify car engines (petrol/diesel) by their sounds. We used the ESC-50 dataset (https://github.com/karoldvl/ESC-50), extracting the engine audio files,
converting them to spectograms and splitting them into different lengths, ending with building and comparing different learners by their success rate.

Project Organization

```
├── files
|   ├── copy_engine_from_ESC-50.ipynb    -> extract soundfiles from ESC-50 dataset
|   ├── edit_soundfiles.ipynb            -> cut and edit soundfiles
|   ├── create_spectogram.ipynb          -> convert soundfiles to spectograms
|   ├── create_dataset.ipynb             -> create_dataset.ipynb
|   ├── merge_dataframes.ipynb           -> merge different dataframes
|   ├── evaluation_learner_v2.ipynb      -> final learner test and results
|   ├── learner_v1.ipynb                 -> first learner test
|   ├── learner_v1.ipynb                 -> second learner test
|   ├── bg_lr_v2_5s_analyse.ipynb        -> third learner test
|   └── datasets                         -> 
|       ├── ESC-50_engine                -> extracted soundfiles
|       ├── ESC-50_engine_spectograms    -> converted spectograms
|       ├── split_test                   -> testing split audio function
|       ├── datasetX_Ysec                -> different datasets for different audio lengths respectively
|   └── pp_raw_data                      -> final labeled sound files, used to train learner
|   └── ESC-50-master                    -> used dataset
```

This project was created as part of 
Contributors include:
