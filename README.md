# Kraken-Taxonomy-Report

Requires biopython to build optional trees.
```
Usage: kraken_taxonomy_report.py [options] file1 file...fileN

Options:
  -h, --help            show this help message and exit
  -v, --version         print version and exit
  --show-zeros          Show empty nodes
  --header-line         Provide a header on output
  --intermediate        Intermediate Ranks
  --name-id             Use Taxa ID instead of Name
  --name-long           Use Long taxa ID instead of base name
  --taxonomy            Output taxonomy in last column
  --cluster=CLUSTER     Cluster counts to specified rank
  --summation           Add summation of child counts to each taxa
  --sanitize-names      Replace special chars ( | |\||\.;) with underscore (_)
  --show-rank           Output column with Rank name
  --db=DB               Name of Kraken database
  --output=OUTPUT       Name of output file
  --output-tree=OUTPUT_TREE
                        Name of output file to place newick tree
```
