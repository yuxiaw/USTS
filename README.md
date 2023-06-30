# Collective Human Opinions in Semantic Textual Similarity
This work explores collective human opinions in Semantic Textual Similarity, with a new uncertainty-aware STS dataset, USTS released.

**USTS** is split into two subsets: **USTS-U and USTS-C** by the degree of annotation disagreement between raters. 
USTS-C has higher human disagreement than USTS-U. Chinese text, raw annotations and average similarity score can be found in ./data/ustsc and ./data/ustsu, with clear split for training, development and test sets.
We additionally provide multilingual USTS with other languages, such as English, Arabic, German, Japanese and etc., and note that the raw annotations are labelled based on the Chinese sentence pairs, see ./data/usts.json.

Annotations used for the multilingual case study investigating the impact of text language and annotator language proficiency on the labelling are in ./data/usts_multilingual_case_study_examples.json, in which field of split indicates the example is from usts-c or usts-u, 100 examples for each subset. 
Under the field of zh, there are Chinese sentence pair, labels assigned by Chinese native speakers (reading Chinese text).
Under the field of en, there are English sentence pair, labels from English native speakers, professional translators, oversea students, general users (reading English text). Translators, students and general users are all Chinese native speakers, they have different level proficiency of English.
