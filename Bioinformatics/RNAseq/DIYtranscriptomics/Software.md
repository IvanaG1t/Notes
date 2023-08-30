## Instaing kallisto

Kallisto is an alining and mapping package designed for bulk and single cell RNA sequencing (scRNA-seq) data. Unfortunatelly, it is only adapted for Mac OS or Unix environments unless you would be willing to go through a [workaround](https://protocols.hostmicrobe.org/conda). Code shown here uses `conda` in Ubuntu 22.04 environment following instructions from _DIY.Transcriptomics_ course from [here](https://diytranscriptomics.com/).

### Alinging and read mapping using `kallisto`

There could be an issue with creating index file from a reference fasta if using `kallisto 0.50.0` saying `Illeagal instructin`. It could be [solved](https://github.com/bioconda/bioconda-recipes/issues/42633) with downgrading to `kallisto 0.48.0` version and then running it. Otherwise, an allready created indices could be downloaded form Patcher Lab's GitHub [page](https://github.com/pachterlab/kallisto-transcriptome-indices/releases).
