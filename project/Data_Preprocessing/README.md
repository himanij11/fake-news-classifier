The `FAKES_Dataset` folder contains the FAKES dataset.
The `ISOT_Dataset` folder contains the ISOT dataset.
The `fnc1_Dataset` folder contains the fnc1 dataset.

The ipynb files are used for preprocessing the **FAKES, ISOT, fnc1 datasets**.

- **ISOT_Data.ipynb** - This ipynb will combine the ISOT dataset and save the combined dataset into the `ISOT_Dataset` folder.

- **fnc1_Data.ipynb** - This ipynb will combine the ISOT dataset and save the combined dataset into the `fnc1_Dataset` folder.

The data preprocessing in each ipynb is done as follows:

1: **Creating a new column in the dataset which was formed by merging the headline of the article with the article body**

2: **Lowercasing the entire text**

3: **Removing URLs and special characters from the text**

4: **Tokenizing the input text** - The input text is split into individual words. We used the word tokenize() which takes a string of text as input and returns a list of tokens.

5: **Removing stopwords from the text** - Common words such as "a","an","the","in" that donot provide much meaning were removed.

6: **Lemmatizing the text** - The text was lemmatized to reduce the tokenized words to their base form. For example, the words such as starts, starting, started will be reduced to start as the base form. The text was then finally vectorized using the tokenizer function of the Keras library. The tokenizer() function was used to convert the text into a sequence of integers, where each integer represents a specific token.

- **FAKES_Data_Preprocessing.ipynb** - This ipynb is used for preprocessing the FAKES dataset and the preprocessed dataset will be saved in the `Preprocessed_Dataset` folder.

- **ISOT_Data_Preprocessing.ipynb** - This ipynb is used for preprocessing the ISOT dataset and the preprocessed dataset will be saved in the `Preprocessed_Dataset` folder.


- **FNC1_Data_Preprocessing.ipynb** - This ipynb is used for preprocessing the fnc1 dataset and the preprocessed dataset will be saved in the `Preprocessed_Dataset` folder.
