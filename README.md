# Non-Intrusive-Speech-Quality-Assessment
Non-Intrusive Speech Quality Assessment

音频质量自动打分工具

# Based on
https://github.com/ConferencingSpeech/ConferencingSpeech2022

https://github.com/gabrielmittag/NISQA

https://github.com/xaddwell/SQA-GAN

# How to use
python run_predict.py --mode predict_dir --pretrained_model weights/best_model.pth --num_workers 0 --bs 10 --data_dir data_waves/ --output_dir mos_out/
