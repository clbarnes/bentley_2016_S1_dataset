NOTES
-----

These are TSV (tab-separated value) files.

The first row is a header describing each column. The number in the 'reference' column refers to the supplementary references (included here in TSV format).

Some receptors (both monoamine and neuropeptide) have been excluded from the analyses in the main body of this study - these are marked with a '1' in the 'excluded' column. See the 'excluded_reason' column for notes. 

Individual neurons are listed, rather than pairs/classes.

Neurons whose name includes a number are not zero-padded, for compatibility with community resources like OpenWorm and WormBase.

The expression data includes some neuropeptides and putative receptors (such as ntr-2) which are not represented in the neuropeptide -> receptor mappings, because of insufficient data suggesting such a mapping. As such, they do not appear in the edge lists or affect our analyses. They are included here for completeness, as a snapshot of the best neuropeptide/ putative receptor expression information we have available on publication.

FILE LIST
---------
monoamine_expression.tsv
monoamine_receptor_expression.tsv
neuropeptide_expression.tsv
neuropeptide_receptor_expression.tsv
neuropeptide_receptor_mapping.tsv
supplementary_references.tsv
