# Israeli Association of Human Language Technologies

IAHLT is a nonprofit organization whose goal is to create annotated datasets
for Hebrew and Arabic. We open-source several of our resources to the public,
and the rest is accessible to fee-paying members only.

## Open resources

Each release comes with scripts and pretrained models. For details, see the README in each repository.

| Resource | Type | Size |
|----------| ---- | ---- |
| [`UD_Hebrew-IAHLTwiki`](https://github.com/IAHLT/UD_Hebrew-IAHLTwiki) | treebank + named entities, conllu + biose | 5k sentences |
| [`UD_Hebrew-IAHLTknesset`](https://github.com/IAHLT/UD_Hebrew-IAHLTknesset) | treebank, conllu | 2.5k sentences |
| [`Arabic-Morphology-IAHLT`](https://github.com/IAHLT/Arabic-Morphology-IAHLT) | morphology, conllu | 2k sentences |

## Member resources

Please contact info@iahlt.org to inquire about access.

| Resource   |      Text Type      |  Quantities |
|--------------|----------------|-----------|
| Hebrew Universal Dependencies |  diverse | 48,000 sentences |
| Hebrew Named Entities | diverse | 47,000 paragraphs |
| Arabic Named Entities | newspaper | 75,000 paragraphs |
| Arabic Morphology | newspaper | 5,973 sentences |
| Arabic transcriptions - Palestinian dialects | diverse | 93,000 tokens|

We also have UD and NER parsers trained over these resources. 

###  Hebrew Universal Dependencies

Our Hebrew treebank consists of over 45k dependency trees, including hundreds
of complete documents, from Hebrew Wikipedia, the entitlement advocacy
organisation Kol Zchut, the technology magazine Geektime, and the news sites
Davar and Israel Hayom.

| Source  | Genres  | no. Sentences  | no. Documents |
| ------  | ------  | -------------  | ------------- |
| Davar  | Hebrew news  | 11224  | 369 |
| GeekTime  | News, writing for the web, sometimes nonstandard Hebrew  | 4213  | 0 |
| Israel Hayom  | Hebrew news  | 386  | 7 |
| Knesset | Knesset protocols | 2883 | 100 |
| Kol Zchut  | Information about entitlements rights of Israelis  | 11214  | 313 |
| Wikipedia  | Biographies, events, locations, legal, medical  | 11309  | 78 |

Two independent annotations for over 6k of the 39k total sentences. Kappa
inter-annotator agreement score per-feature.

### Arabic Morphology

Our Arabic lemmatisation and part-of-speech tagging corpus consists of 5973
annotations of 4869 sentences (with a total of 171722 tokens annotated, 12190
unique lemmas) for lemma and part-of-speech. The texts were sampled from the
news articles. For the multiply-annotated sentences, inter-annotator agreement
statistics are included.

### Arabic and Hebrew Named Entities

Our named entities corpus includes over 123k paragraphs, over 11k documents in
Arabic and Hebrew, annotated for 13 entity types.

| Language  | Source  | no. Paragraphs  | no. Articles |
| --------  | ------  | --------------  | ------------ |
| Hebrew  | Davar, Israel Hayom, Knesset protocols, and Wikipedia | 47k  | 2923 |
| Arabic  | News | 75k  | 8342 |

### Palestinian Arabic Transcriptions

Our Palestinian Arabic corpus consists of 90k tokens of transcribed text from
32 YouTube videos. Ten of these videos were independently annotated twice to
study inter-annotator agreement; the annotations and our calculated agreements
are included.

 | Year  | Videos  | Duration (min)  | no. Tokens |
 | ----  | ------  | --------------  | ---------- |
 | 2010-2014  | 4  | 18  | 2131 |
 | 2015-2019  | 19  | 484  | 37026 |
 | 2020-  | 11  | 686  | 47129 |

