# Merged annotations

This directory contains a single csv file in which the verb-argument (H. Hettrich) and the morpho-lexical annotations (O. Hellwig) are presented in a merged format.

The layout of the file resembles that in the folder *morpho-lexical*, but $ is used as separation character.

##Fields with different names (morpho-lexical level):
* **lex_id** = morpho-lexical$lemma_id
* **boundary** = morpho-lexical$sentence_boundary
* **udpos** = morpho-lexical$coarse_pos
* **cas**(e)
* **num**(ber)
* **gen**(der)
* **per**(son)
* **tem** = morpho-lexical$tense_mode

## Fields describing the verb-argument level
* **instance_id**: unique identifier of the verb-argument structure. All instances (lines) that share a number belong to the same verb-argument construction.
* **kasus**: as annotated by H. Hettrich
* **semantik**: word semantic class as annotated by H. Hettrich
* **funktion**: case semantic function as annotated by H. Hettrich
* **annotation_mode**: How was this argument annotated?
 * def: By direct match between Hettrich and Hellwig data
 * heu: Using a heuristic (refer to the paper)
 * oh: Later annotation by O. Hellwig (use with care!)
* **annotation_problems**: If no direct match between Hettrich and Hellwig was possible, this field indicates possible sources of problems
* **num_anno_problems**: Number of such problems (integer)