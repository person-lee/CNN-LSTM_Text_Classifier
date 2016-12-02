# CNN-LSTM_Text_Classifier
Text classification (specifically for Sentiment Analysis) using Deep Learning
THEANO_FLAGS=mode=FAST_RUN,device=gpu0 python training.py files/configuration_file.csv files/layers_lstm_static.csv NO_MODEL NO_STATIC NO_NONSTATIC save files/sst3_data/sst3_test.csv files/sst3_data/sst3_train_sentences.csv
