# *Clematoclethra scandens* reference genome

This repository provides the frozen chromosome-level *Clematoclethra
scandens* reference assembly and structural annotation used in the comparative
gene-loss analyses of *Actinidia*.

## Dataset

| Item | Description |
| --- | --- |
| Sample | JZP036 |
| Assembly | 24 chromosome sequences; 493,682,713 bp |
| Sequence format | Soft-masked FASTA |
| Annotation | GFF3; 35,558 gene models and 41,457 mRNA records |
| Public sequence-database accession | Pending |

## Download

The files are distributed as assets of the
[`reference-genome-v1`](https://github.com/lemonral/Clematoclethra-scandens-genome/releases/tag/reference-genome-v1)
release because the compressed genome exceeds GitHub's normal Git file-size
limit.

- `Clematoclethra_scandens.genome.fasta.gz`
- `Clematoclethra_scandens.annotation.gff3.gz`

Checksums for both compressed assets and their decompressed source files are
provided in [`checksums/`](checksums/). The decompressed checksums match the
frozen inputs used by the manuscript analysis.

## Scope

This is the exact reference dataset used for the gene-loss workflow. It is
provided as a versioned research data release while deposition in a public
sequence archive is pending.
