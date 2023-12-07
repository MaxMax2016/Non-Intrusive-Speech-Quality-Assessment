# Non-Intrusive-Speech-Quality-Assessment
Non-Intrusive Speech Quality Assessment

# Based on
https://github.com/ConferencingSpeech/ConferencingSpeech2022

https://github.com/gabrielmittag/NISQA

https://github.com/xaddwell/SQA-GAN

# How to use
python run_predict.py --mode predict_dir --pretrained_model weights/best_model.tar --num_workers 0 --bs 10 --data_dir ../data/waves/ --output_dir mos_out
