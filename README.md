# Collecting-Data-Assignment-4-corpus
# Description
This repository contains a total of 17 text files of British and American modernist poetry, a preprocessed and cleaned corpus file, and a Jupyter Notebook that provides text preprocessing and data cleaning steps.

# Columns in the corpus
| Columns        | Description            | Data Type    |
|-----------------|------------------------|--------------|
| Filename       | name of the poems       | string       |
| Title           | poem name              | string       |
| Release Date    | Publication date       | string       |
| Author          | author name             | string       |
| Tokenize         | tokens of the text      | string       |
| POS_tags         | part of speech of tokens | string       |
| Lemmatized       | lemmas of tokens        | string       |
| Text             | original (untokenized) text of each poem      | string       |


# Purpose of the corpus
This corpus aims to provide researchers, students, and modernist poetry enthusiasts with some English and American modernist poetry texts. This corpus can be used for literary research, style analysis, emotional analysis, and other research. Future research can focus on exploring the themes, stylistic differences among these poems. In addition, these texts can also be used for natural language processing research, such as sentiment analysis, text generation, and language model training.

# Criteria for Text Selection:
①Why——These authors and poetic works are important representatives of 20th century British and American modernist literature, and have a significant influence on the development of British and American modernist literature. And these works reflect the changes in the social, political, and cultural environment at that time. Conducting in-depth research on these works helps to understand the development of modernist literature.

②Source-https://dataverse.harvard.edu/dataset.xhtmlpersistentId=doi:10.7910/DVN/F9XM79

## License
Project Gutenberg does not permit the deletion of text from documents bearing the Gutenberg License.(So the preface at the beginning of the text - i.e. "Project Gutenberg e-book..." cannot be deleted)

## File Format in the Corpus

The corpus data is stored in CSV format.

# Pre-processing
- Create a DataFrame and extract metadata information
- Extract original text content

# Cleaning Process
- Clear HTML tags from text
- Tokenization
- Lemmatization
- Part-of-Speech Tagging

# Annotations and Tools Used
These Python code snippets mainly use tools such as Pandas and spaCy to process text. Pandas was used to create a data frame to extract the metadata information of the file, and spaCy was used to tokenization, part-of-speech tagging and lemmatization of the text.

