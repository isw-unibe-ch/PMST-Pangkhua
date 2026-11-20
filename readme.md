# Person Marking in South-Central Trans-Himalayan: Pangkhua

This PARALEX set contains person markers in Pangkhua, including inflected verbal forms and pronouns. It constitutes part of the PMST (Person Marking in South-Central Trans-Himalayan) database.
The PMST database is a collection of person forms from a broad sample of South-Central Trans-Himalayan languages collected with a common methodology and published as PARALEX sets. PMST sets can be used both for describing and analyzing language-internal distributions and for comparison of person forms.

The general design principles of PMST are described in Auderset et al. 2026. Files and columns are described here only where they deviate from the PARALEX standard.
For more details about the data, please consult the data_sheet.md in the docs folder.

* PMST diverges most from the PARALEX standard and design principles in that the verb forms are abstract and do not contain a lexical verb stem. In its place, we use Σ as a placeholder (as is common in Trans-Himalayan linguistics). This means that there is no lexeme table and the data set cannot be used to study variation in verb stems.
* The source_form column in the forms file contains the data exactly as it appears with in the source. This may include a lexical verb stem (listed in lexemes). In the orthgoraphic and phonological representation, the lexical verb is replaced by a Σ (as there are no inflectional classes). This placeholder also appears in the graphemes and sounds files for validation purposes.
* The lexemes file is kept relatively minimal and only lists each lexical stem in orthographic form and its meaning. This is because we do not always have access to forms with stems. For pronouns, "no_stem" is indicated in the lexeme column in the forms file and verb forms without a stem are labeled "abstract_entry". These are also listed in the lexemes file (for validation purposes).
* To facilitate comparison across PMST data sets, each file has an additional column with a language identifier. This means that files can be combined from different PMST sets without losing information.
* The morphs file contains a list of all morphs that appear in the data set (apart from the stem) in tokenized IPA. For each morph there is a list of all the forms and cells it appears in. 
* The docs folder contains the data sheet with more extensive description of how the data was gathered.

## Additional information specific to Pangkhua

* Tone: Pangkhua is described as having lexically contrastive high and low tone, though only a small number of elderly speakers make or discern this contrast (Akter 2024:57-58). According to the descriptive materials, tonal minimal pairs have collapsed into homophone pairs for the majority of speakers, especially those of younger generations. As such, Pangkhua can be understood as undergoing a process of tonoexodus. During the fieldwork trips in which the data contained in this data set were collected, opportunity for working with speakers for whom tonal contrasts are still operative was limited, and the data which were collected could not be cross-checked. As such, tonal values are not marked here. 
* Optional marking of 3rd person: The pre-root 3rd person agent agent marker can be freely omitted for certain co-argument scenarios in the nonfuture-affirmative transitive indicative construction. 
* Label mapping: The labels used in this data set for indicative constructions with different tense-polarity configurations (nonfuture-affirmative, nonfuture-negative, future-affirmative, future-negative) match those used in descriptive materials on Pangkhua person indexation (e.g. Akter 2024:266-267). 



## References

Auderset, Sandra, Hunter L. Brown, Jonathan Reich, Pascal Gerber, Muhammad Zakaria, and Linda Konnerth. 2026. “A Database of Person Marking in South-Central Trans-Himalayan”. *Journal of Open Humanities Data* 12 (1): 58. https://doi.org/10.5334/johd.505.

Akter, Zahid. 2024. _A Grammar of Pangkhua_. Berlin, Boston: De Gruyter Mouton.

Akter, Zahid. 2024. _Argument indexation on verbs in Pangkhua and South Central Tibeto-Burman (Kuki-Chin)_. *Linguistics of the Tibeto-Burman Area* 47 (2): 284-317. https://doi.org/10.1075/ltba.00022.akt.
