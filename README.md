# CSVScreenTax
# Language: Python
# Input: TXT
# Output: CSV
# Tested with: PluMA 1.1, Python 3.6
# Dependency: numpy==1.16.0

PluMA plugin to remove all samples from a configuration file
that do not satisfy a given critera (zero or nonzero) for a particular
taxon.  

This works like the CSVScreen plugin, except the taxon can be
at any level of the phylogenetic tree (i.e. in the example,
family Veillonellaceae).

The plugin accepts as input a TXT file of keyword-value pairs:
csvfile: Input CSV
taxon: Taxon name
level: Level of phylogenetic tree
criteria: zero or nonzero

Output CSV file will be the screened input CSV file.
