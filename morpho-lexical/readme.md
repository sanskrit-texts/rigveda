# Morpho-lexical annotations

The file 'rigveda.csv' contains the morpho-lexical annotations that were generated with the SanskritTagger tool and manually validated.

The file is a plain text file in UTF-8 encoding using # for separating fields.

The first line of the file contains the headline. Explanation of the individual fields:
* **book** of the Rigveda
* **chapter** = hymn of the Rigveda
* **strophe** = stanza
* **verse** = line in the stanza. A line is terminated by a (double) danda.
* **position** of a word in this line. Words are separated by spaces in the samhita text.
* **word** = a string of the samhita text; can contain multiple inflected lemmata.
* **substring_position**: If a word consists of multiple lemmata, this value gives the position of the lemma.
* **surface_form**: ''padapatha'' form of an inflected lemma
* **lemma**: dictionary form of the lemma
* **verbal_root**: If the lemma is a verb, this is the root without prefixes. Ex.: lemma=abhigam, root=gam
* **verbal_prefixes**: If the lemma is a prefixed verb, these are the concatenated prefixes. Ex.: lemma=abhyupagam, prefixes=abhyupa
* **lemma_id**: unique lemma id
* **id_tea**: unique id of the lemma at this position (internal use only)
* **sentence_boundary**
coarse_pos#case#number#gender#person#tense_mode#synsets