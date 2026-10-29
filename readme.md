# Person Marking in South-Central Trans-Himalayan: Anal Naga

This PARALEX set contains person markers in Anal Naga, including inflected verbal forms and pronouns. It constitutes part of the PMST (Person Marking in South-Central Trans-Himalayan) database.
The PMST database is a collection of person forms from a broad sample of South-Central Trans-Himalayan languages collected with a common methodology and published as PARALEX sets. PMST sets can be used both for describing and analyzing language-internal distributions and for comparison of person forms.

The general design principles of PMST are described in Auderset et al. 2026. Files and columns are described here only where they deviate from the PARALEX standard.
For more details about the data, please consult the data\_sheet.md in the docs folder.

* PMST diverges most from the PARALEX standard and design principles in that the verb forms are abstract and do not contain a lexical verb stem. In its place, we use Σ as a placeholder (as is common in Trans-Himalayan linguistics). This means that there is no lexeme table and the data set cannot be used to study variation in verb stems.
* The source\_form column in the forms file contains the data exactly as it appears in the source. This may include a lexical verb stem (listed in lexemes). In the orthgoraphic and phonological representation, the lexical verb is replaced by a Σ (as there are no inflectional classes). This placeholder also appears in the graphemes and sounds files for validation purposes.
* The lexemes file is kept relatively minimal and only lists each lexical stem in orthographic form and its meaning. This is because we do not always have access to forms with stems. For pronouns, "no\_stem" is indicated in the lexeme column in the forms file and verb forms without a stem are labeled "abstract\_entry". These are also listed in the lexemes file (for validation purposes).
* To facilitate comparison across PMST data sets, each file has an additional column with a language identifier. This means that files can be combined from different PMST sets without losing information.
* The morphs file contains a list of all morphs that appear in the data set (apart from the stem) in tokenized IPA. For each morph there is a list of all the forms and cells it appears in.
* The docs folder contains the data sheet with more extensive description of how the data was gathered. It also contains a plot showing the distribution of each morph across most relevant grammatical categories.


## Additional information specific to Anal Naga

* Tone: Anal Naga has contrastive tone. Low tone is marked with a grave accent and high tone with an acute accent, or tones are marked with numbers (1 = low, 5 = high). There are also toneless morphemes, which are left unmarked in both the orthography and the IPA. Note that there are differences in tonal analysis between this data set and data in Ozerov (2018; 2019): Person prefixes are now analyzed as toneless, and tones in the transitive non-future generic forms have been adjusted where the plural suffixes are involved. Tonal research is still ongoing. Also note that there’s a typo in Table 11 on p.52 in Ozerov 2019: instead of táː-jéː-nʉ́ it should be tà-jéː-nʉ́ (cp.p.43)
* Descriptive statement on Anal Naga transitive indexation: Mostly, local scenarios feature double indexation of A and O; 3->SAP forms feature O indexation; and third person O forms feature A indexation. Since 3rd person in some person marker sets is not marked, the description can vary depending on whether this is considered as being unmarked or being a zero index.
* Mapping between database paradigm labels and Anal Naga descriptive labels:
  
    Database label = Language-specific descriptive label
  
        - fut.aff = future affirmative
        - fut.neg = future negative
        - nfut.aff = 2 paradigms: generic and non-generic (affirmative)
        - nfut.neg = 2 paradigms: generic and non-generic (negative)

The generic paradigm of non-future affirmative forms is included because it provides unusual forms with special stems. In order to create a comprehensive data set, the generic paradigms are also included for the non-future negative even though these forms do not add any special forms but function the same way as the non-generic non-future negative in terms of person marking.

* Decisions
  1. In the forms tagged "generic" in the “nfut.aff” paradigm, first person forms (both intransitive and transitive) induce both vowel lengthening (if the root is an open CV syllable) and a high tone on the stem. This is not recognizable in the morpheme-by-morpheme segmentation but only in the source forms. There is a tag “special\_stem” to signal this. (If there is a plural marker, the vowel lengthening and high tone occurs there: in those cases, this changed plural marker is treated as an allomorph.)
  
  2. Similarly, in the future affirmative paradigm, in forms involving first or second person the future marker /-na/ does not occur – instead, again, we find both vowel lengthening (if the root is an open CV syllable) and a high tone on the stem, signalled by the tag "special\_stem". (Again, if there is a plural marker, the vowel lengthening and high tone occurs there: in those cases, this changed plural marker is treated as an allomorph.) See also the remarks by Ozerov:
     * future marker is /-na/ but it disappears in 1/2 forms changing the tone of the preceding syllable to high (if it is low), and lengthening it if it is open. It also changes the assignment of tones to the following syllables. In the example here, tà ‘touch’ is open short, so at least the length part can be represented as if it were a separate morpheme. (e.g. 1SG->3SG). However, in case of plural, the future follows the plural marker (e.g. 3SG->3PL tà-jè-ná-ká ‘touch-3PL-FUT-AFF’). Again, the 3PL marker is a short open syllable, so it gets lengthened in SAP forms too (as in 1SG->3PL). But the SAP.PL marker is /-hin/, and it changes the tone as the result of dropping the FUT-marker /-na/ – compare 2PL->1SG vs. 3PL->1SG. So /-hín/ in cases above represents two morphemes: SAP.PL+FUT.
  
        ka-ː-tà-jè-ná-ká		ka-ː-tà-hín-ká-tí	(as if	ka-ː-tà-hìn-(ná)-ká-tí > ka-ː-tà-hín-ká-tí)
        1-P-touch-3PL-FUT-AFF	1-P-touch-SAP.PL\\FUT-AFF-2
        ‘They will touch me’		‘You-all will touch me’

* Data uncertainties
  
  1. Reported by Ozerov, p.c.: In SAP<-->3 scenarios, there are two competing PL markers – the SAP.PL /-hin/ and the 3PL /-je/. They do not appear to be compatible with each other, but that’s not entirely clear. In SAP.SG-->3PL scenarios, it is apparently the SAP.PL /hin/ that wins out, (3PL /-je/ is reserved for SAP.SG-->3PL), but in SAP.PL <--> 3PL both options appear to be possible
   
  2. Regarding the inclusive pronouns: “There are two competing forms of the independent INCL pronoun, with or without the initial nasal: àní/nàní. The difference between the two is yet unclear; they are found interchangeably in the speech of both genders from all generations and dialects with no clear meaningful, contextual or socio-pragmatic difference.” (Ozerov 2019: 28)


## References

Auderset, Sandra, Hunter L. Brown, Jonathan Reich, Pascal Gerber, Muhammad Zakaria, and Linda Konnerth. 2026. “A Database of Person Marking in South-Central Trans-Himalayan”. *Journal of Open Humanities Data* 12 (1): 58. https://doi.org/10.5334/johd.505.

Ozerov, Pavel. 2018. "Tone assignment and grammatical tone in Anal (Tibeto-Burman)". *Studies in Language* 42 (3): 708-733. https://doi.org/10.1075/sl.17030.oze.

Ozerov, Pavel. 2019. "Person indexation in Anal". *Himalayan Linguistics* 18 (1). https://doi.org/10.5070/H918142426.

Ozerov, Pavel and Linda Konnerth. 2021. "Multiple functions of the inclusive: examining synchronic variation in light of diachronic shift in South-Central Trans-Himalayan". *Folia Linguistica* 55: 175-204. https://doi.org/10.1515/flin-2021-2018.
