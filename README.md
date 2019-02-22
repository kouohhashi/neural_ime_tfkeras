## neural_ime with tf.keras
This is a deep learnig based model which convert Japanese hiragana into kanji and hiragana mixed. The original source code is written by @yoh_okuno and I modified the codes to work with tensorflow 1.12.0 and tf.keras.
Credit: @yoh_okuno
Original source code is [here](https://github.com/yohokuno/neural_ime).

You can test this kanakanji_convert_4_train.ipynb to train a model and test the model with kanakanji_convert_4_check.ipynb. The datasets is wiki_dataset_mecab_80000.txt, which is a Japanese hiragana and kanji hiragana mixed pair originally from Wikipedia.
uno
