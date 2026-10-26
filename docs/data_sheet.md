Data set name: PMST Anal Naga

Data set developer(s): Pavel Ozerov, Linda Konnerth, Sandra Auderset

Data sheet author(s): Pavel Ozerov, Linda Konnerth

Others who contributed to this document: Thotson Langhu


# Motivation

**For what purpose was the data set created?**

This data set was created to investigate the dynamics of person forms in Anal Naga and other South-Central Trans-Himalayan languages.
Further background and motivation can be found in Auderset et al. 2026. Full citation: Auderset, Sandra \& Brown, Hunter L. \& Reich, Jonathan \& Gerber, Pascal \& Zakaria, Muhammad \& Konnerth, Linda. 2026. A Database of Person Marking in South-Central Trans-Himalayan. Journal of Open Humanities Data 12(1), 58. (doi:https://doi.org/10.5334/johd.505).

**Who created the data set (for example, which team, research group) and on behalf of which entity (for example, company, institution, organization)?**

The data set was created by a team of researchers at the Department of Linguistics at the University of Bern (PI Linda Konnerth) in collaboration with local linguists and language experts in Northeast India.

**Who funded the creation of the data set?**

This work is funded by SNSF (Swiss National Science Foundation) Grant 10000946 to Linda Konnerth at the University of Bern.


# Composition

Paralex data sets document paradigms of inflected forms.

**Are forms given as orthographic, phonetic, and/or phonemic sequences?** 

Forms are provided as orthographic and phonemic sequences.
The orthography is either the practical one used by the community or a version of the IPA used by linguists and language experts.
For Anal Naga, it is a version of the IPA.

**How many instances are there in total?**

-   Number of inflected forms: 311

-   Number of unique inflected forms: 170

-   Number of unique scenarios (person, number, TAM, polarity combinations): 184

-   Number of inflected forms per paradigm and subparadigm:

|paradigm |variants_tag |paradigm_tag  |analysis_tag |overabundance_tag |  n|
|:--------|:------------|:-------------|:------------|:-----------------|--:|
|pron     |pragm_marked |              |             |                  |  2|
|pron     |unspecified  |              |             |optional_plural   |  2|
|pron     |unspecified  |              |             |                  |  8|
|fut.aff  |pragm_marked |              |             |                  |  5|
|fut.aff  |unspecified  |hort          |             |                  |  5|
|fut.aff  |unspecified  |              |special_stem |                  |  6|
|fut.aff  |unspecified  |              |             |                  | 33|
|fut.neg  |pragm_marked |              |             |                  |  6|
|fut.neg  |unspecified  |              |             |                  | 44|
|nfut.aff |pragm_marked |generic_nfut  |             |                  |  6|
|nfut.aff |pragm_marked |ngeneric_nfut |             |                  |  6|
|nfut.aff |unspecified  |generic_nfut  |special_stem |                  |  3|
|nfut.aff |unspecified  |generic_nfut  |             |                  | 41|
|nfut.aff |unspecified  |ngeneric_nfut |             |                  | 44|
|nfut.neg |pragm_marked |generic_nfut  |             |                  |  6|
|nfut.neg |pragm_marked |ngeneric_nfut |             |                  |  6|
|nfut.neg |unspecified  |generic_nfut  |             |                  | 44|
|nfut.neg |unspecified  |ngeneric_nfut |             |                  | 44|


**Language varieties**

-   BCP-47 language tag: NA
-   Glottocode: anal1239
-   Language variety description: Anal Naga is spoken by 20,000 people primarily in Chandel District, Manipur.

**Does the data pertain to specific dialects, geographical locations, genre, etc?**

The data was collected in Chandel town. Dialectal variation does not seem to have much impact on person marking, therefore the present data is assumed to be largely representative of the Anal Naga language.

**Does the data set contain all possible instances or is it a sample (not necessarily random) of instances from a larger set?** 

The data set contains all person forms found in the language, both verbal indexes and pronouns. Hortative forms were not included in the data set (see below for exceptions).

**Is any information missing from individual instances?** 

In the intransitive and transitive future affirmative paradigms, there are gaps for scenarios with an inclusive S/A argument. In these cases, hortative forms are used instead.

**Are there any errors, sources of noise, or redundancies in the data set?** 

No.

**Is the data set self-contained, or does it link to or otherwise rely on external resources (for example, websites, tweets, other data sets)?** 

The data set is self-contained.

**If linking to vocabularies from other databases (such as databases of features, cells, sounds, languages, or online dictionnaries), were there any complex decisions in the matching of entries from this data set to those of the vocabularies (eg. inexact language code)?**

NA

**Does the data set contain data that might be considered confidential (for example, data that is protected by legal privilege or by doctor-patient confidentiality, data that includes the content of individuals' non-public communications)?**

The data set pertains to small or indigenous language communities, namely those of the Anal Naga people in Manipur and adjacent regions.
The data are published here with the consent of the community, specifically including the approval of the community leaders (ANTA).


# Collection process

**What is provenance for each table (lexemes, cells, forms, frequencies, sounds, features), as well as for segmentation marks if any? Are any information derived from other data sets?** 

The data comes from fieldwork conducted by Pavel Ozerov. Specific forms were taken from a combination of a text corpus, elicitation, and field notes. This work also forms the basis for the segmentation. 

**How were paradigms separated (eg. in the case of homonyms or variants)? What theoretical or practical choices were made?**

Design principles and theoretical choices implemented for this data set are explained in Auderset et al. 2026.

**How was the paradigm structure (set and labels of paradigm cells) decided? What theoretical or practical choices were made?**

Design principles and theoretical choices implemented for this data set are explained in Auderset et al. 2026.

**What is the expertise of the contributors with the documented language?** 

Pavel Ozerov: linguist specializing in South-Central Trans-Himalayan, currently working on a grammar of Anal Naga

Thotson Langhu: native speaker consultant

**Who was involved in the data collection process (for example, students, crowdworkers, contractors) and how were they compensated (for example, how much were crowdworkers paid)?**

Only the contributors listed at the beginning of this file.

**Over what timeframe was the data collected?** 

The data was collected between 2015 and 2025.


# Preprocessing/cleaning/labeling

**How were the inflected forms obtained?**

All forms were collected from speakers (see above).

**How were the phonological or phonemic transcriptions obtained?** 

The phonological transcriptions were generated with the qlcData package in R using an orthography profile that maps graphemes to IPA.
The mappings are based on the phonological analysis of the language.

**If relevant, how were the forms segmented?**

Manually based on expert knowledge.

**Was any preprocessing/cleaning/labeling of the data done (for example, discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values, cleaning of labels, mapping between vocabularies, etc)?** 

No.

**Was the "raw" data saved in addition to the preprocessed/cleaned/labeled data (for example, to support unanticipated future uses)?**

Yes (not publicly available yet).

**Is the software that was used to preprocess/clean/label the data available?** 

The data was prepared for Paralex with the open source software R using RStudio.


# Uses

**Has the data set been used for any published work already?** 

No.

**What (other) tasks could the data set be used for?**

It can be used for descriptive and comparative analyses.

**Are there tasks for which the data set should not be used?**

No.


# Distribution

**Will the data set be distributed to third parties outside of the entity (for example, company, institution, organization) on behalf of which the data set was created?**

No.

**How will the data set be distributed (for example, tarball on website, API, GitHub)?** 

The data set is available on GitHub at https://github.com/isw-unibe-ch and on Zenodo as part of the Paralex collection at https://doi.org/10.5281/zenodo.17881855.

**Will the data set be distributed under a copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)?** 

The data set is distributed under a CC-BY-SA 4.0 license.


# Maintenance

**If others want to extend/augment/build on/contribute to the data set, is there a mechanism for them to do so?** 

For suggestions or error reports please open an issue on GitHub.