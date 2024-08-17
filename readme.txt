Training:
- Populate the dataset folder
- qsub job.pbs > will run Real-ESRGAN/train.sh
- Current script is written to use 4 GPUs parallely

My results:
- My GPU job run logs can be seen in file: train.o6865657
- HQ images generated using my best model (19500th iteration) can be found here: results/train_SRResNet_x4_FFHQ_300k_infer195000
- My best model checkpoint (19500th iteration) can be found here: results/net_g_195000.pth
- Training log file: train_SRResNet_x4_FFHQ_300k.csv

Re-produce best results:
- Populate the dataset folder
- run "python infer.py" > This will create the best images