Samples of TEI XML for a source text and translation
where translation aligment and treebank data has been merged
into the tokenized words in the TEI XML.

Each aligned or treebanked word is wrapped in a `<w/>` tag. The relation keyword
is supplied in the `@ana` attribute of the `<w/>` tag, and the translation 
alignment in the `@corresp` attribute. The value in the `@corresp` attribute
is an xpointer into the corresponding TEI file for the aligned translation. 
There may be more than aligned word for any given word. Multiple xpointers are
separated by spaces in this case.


