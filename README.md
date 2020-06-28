# dcase-2020-task1-subtaskB

This repository includes our metadata and code for the submission of IMT Atlantique - BRAIN to the DCASE 2020 challenge, Task 1, subtask B. 
Our technical report is [here](Farrugia_IMT-Atlantique-BRAIn_task1_technical_report.pdf)

Metadata
--

For each of the four submitted model : 

- metadata of our submissions in yaml files
- Detailed parameter counts, layer-wise (Model_X.csv)
- Detailed loss per category and summary of pruning (log_modelX.txt)


Code
--
Pytorch code for training, pruning, finetuning and quantization code will be uploaded in the next days. 

For now we provide :
- the script that was used to [resample the dataset to 18 kHz](resample.py), 
- the [model definitions](models.py).

Code is based on pytorch (1.5), sklearn, pandas, numpy, scipy.

## Resample at 18 kHz
Dataset from TAU 2020 DCASE subtask B can be download at [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3670185.svg)](https://doi.org/10.5281/zenodo.3670185)

To resample run,
```
python resample.py --URL_sound [path dataset] --URL_out [save path]
```

Pretrained models 
--
Pretrained models will be uploaded after the challenge deadline.

Team members
--
- Nicolas Pajusco
- Richard Huang
- Nicolas Farrugia (PI)
  
Acknowledgments to Carlos Lassance, Ghouthi Boukli Hacene, Vincent Gripon and other members of BRAIN for feedback, comments and informal discussions regarding this submission. 
