# Morpho-lexical annotations

The file 'rigveda.csv' contains the morpho-lexical annotations that were generated with the SanskritTagger tool and manually validated by O. Hellwig.

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
* **coarse_pos**: Approximate POS tag (may be incorrect for pronominal classes, doesn't distinguish between common nouns and named entities)
* **case** of a noun or adjective
* **number** of a noun, adjective or verb
* **gender** of a noun or adjective
* **person** of a finite verbal form
* **tense_mode** of a finite verbal form
* **synsets**: (internal use only)
