Hai Frands !
to run the caption module :
python caption_generation.py --rnn-model ./data/caption_en_model40.model --cnn-model ./data/ResNet50.model --vocab ./data/MSCOCO/mscoco_caption_train2014_processed_dic.json --gpu -1 --img ./sample_imgs/tree.jpg 
Use your own images as arguments here.

python caption_generator.py 
runs with default arguments.
