# IAHLT Open Repositories

IAHLT is a nonprofit organization whose goal is to create annotated datasets for Hebrew and Arabic. We open-source several of our resources to the public, and the rest is accessible to fee-paying members only.
Down the page, you have links to our open resource; our full nonopen resources include:

| Resource   |      Text Type      |  Quantities |
|--------------|----------------|-----------|
| Hebrew Universal Depdencies |  diverse | 40,000 sentences |
| Hebrew Named Entities | diverse | 47,000 paragraphs |
| Arabic Morphology | newspaper | 5,000 sentences |
| Arabic Named Entities | newspaper | 75,000 paragraphs |
| Arabic Morphology | newspaper | 5,000 sentences |
| Arabic transcriptions - Palestinian dialects | diverse | 72,300 tokens|

We also have UD and NER parsers trained over these resources.

Please contact info@iahlt.com for more information.

## Linguistically Annotated Resource

### Hebrew Universal Dependencies

1. The Hebrew-IAHLTwiki treebank consists of 5,000 contemporary Hebrew sentences representing a variety of texts originating from Wikipedia entries. It includes various text domains, such as: biography, law, finance, health, places, events and miscellaneous.
2. IAHLTKnesset – Further UD annotations of 2,619 sentences from the Knesset protocols.

### Hebrew Named Entities

In this project, we aim to annotate various types of named entities in Hebrew texts. Our annotation focuses on identifying and categorizing entities such as persons, organizations, locations, events, time expressions, works of art, products, languages, titles, and miscellaneous entities. Additionally, we have a category called "informal" (INF) to capture informal entities.

To ensure comprehensive coverage, we use the following abbreviations to represent each entity type:

- PER: Person
- ORG: Organization
- LOC: Location
- EVE: Event
- TIMEX: Time Expression
- WOA: Work of Art
- ANG: Product
- GPE: Language
- TTL: Title
- MISC: Miscellaneous
- INFORMAL: Informal Entity

### Arabic Morphology

The IAHLT Arabic lemmatisation corpus is a valuable resource that provides annotations for lemma and part-of-speech of Modern Standard Arabic texts used in Israel. This corpus serves as an essential tool for natural language processing (NLP) tasks, enabling researchers and developers to analyze and understand the linguistic properties of Arabic texts. By providing annotations for lemmas and part-of-speech, this corpus supports various NLP applications, such as language modeling, text classification, sentiment analysis, and machine translation. Researchers can leverage this resource to enhance Arabic NLP systems and facilitate deeper linguistic analysis of Arabic language data.


### Arabic Named Entities

Equivalent to the Hebrew Named Entities project above.

### Hebrew Video Transcriptions

The IAHLT Palestinian Arabic corpus is a valuable resource consisting of transcribed texts from Creative Commons YouTube videos in Palestinian Arabic. The corpus serves as an annotation effort aimed at modeling the language used in social media and aiding text-to-speech systems. The transcriptions, following standardized guidelines, provide insights into the linguistic characteristics and variations of Palestinian Arabic. By leveraging this corpus, researchers and developers can enhance their understanding of the language, improve social media language modeling, and develop more accurate text-to-speech systems specific to the Palestinian Arabic dialect.


## Parsers

### HebPipe

HebPipe, developed by Amir Zeldes for IAHLT, is an advanced parser designed specifically for commercial applications. It utilizes cutting-edge techniques, such as the biaffine approach, to accurately analyze the grammatical structure of Hebrew text. By incorporating state-of-the-art models like AlephBERT, HebPipe ensures precise representation of input text. Its exceptional performance in various parsing tasks, including segmentation, lemmatization, and parsing accuracy, makes it a powerful tool for commercial users seeking reliable and high-quality language analysis. Whether you're building chatbots, developing natural language processing applications, or improving text understanding, HebPipe offers industry-leading parsing capabilities for enhancing the efficiency and accuracy of your language-based solutions.


### Arabic trankit model for morphology

IAHLT has developed a freely available udpipe model that performs various linguistic analyses, including sentence segmentation, tokenization, lemmatization, and part-of-speech tagging. This model is trained on a dataset of 2,000 sentences and is designed to provide accurate linguistic annotations for text processing tasks. To access the udpipe model, you can install it using pip for Python usage or clone and compile it for command-line interface (CLI) usage. The detailed instructions for installation and usage can be found in the provided documentation.

