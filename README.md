## Reference files for diffalign performance experiments

Used in: diffalign: a bioinformatics tool for mapping conserved and specific regions in large unaligned sequence sets to guide molecular assay design

This repo contains the sequence set used for performance comparison experiments (See results section 3.4).

- flua_pdm09_m_refseq.fasta         -> template sequence (Influenza A, pdm09, segment 7, NC_026431.1)
- FluA_m_1y_0806_sequences.fasta    -> query/reference set (Influenza A segment 7, 12418 sequences)

### Usage:

Requires diffalign (https://github.com/ssVyz/diffalign).

Requires diffalign.ini to be configured for the specific test cases.

run: diffalign flua_pdm09_m_refseq.fasta FluA_m_1y_0806_sequences.fasta -o [output-path/filename.json] --timer [additional arguments depeneding on test case]

