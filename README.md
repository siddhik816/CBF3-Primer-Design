# Sequence-Based Investigation and Primer Design of CBF3 in *Arabidopsis thaliana*

## Project Overview

This project focuses on the computational investigation and in-silico primer design of the CBF3 (DREB1A) gene from *Arabidopsis thaliana*.

The nucleotide sequence was retrieved from NCBI GenBank, and the coding sequence (CDS) was examined using ApE software. A forward and reverse primer pair was selected and evaluated using NCBI Primer-BLAST and IDT OligoAnalyzer.

## Aim

To retrieve the CBF3 gene sequence, identify its coding region, select suitable forward and reverse primers, and evaluate their properties through computational analysis.

## Gene Information

| Parameter | Details |
|---|---|
| Gene | CBF3 / DREB1A |
| Organism | *Arabidopsis thaliana* |
| Gene ID | 828652 |
| Locus ID | AT4G25480 |
| Accession Number | AF074602.1 |
| Sequence Length | 902 bp |
| CDS Coordinates | 113–763 |
| CDS Length | 651 bp |

## Tools and Databases

- **NCBI GenBank:** Retrieval of the CBF3 mRNA sequence.
- **ApE (A Plasmid Editor):** Identification of the coding sequence and primer selection.
- **NCBI Primer-BLAST:** Primer evaluation and target specificity analysis.
- **IDT OligoAnalyzer:** Hairpin, self-dimer and heterodimer analysis.

## Selected Primer Sequences

| Parameter | Forward Primer | Reverse Primer |
|---|---|---|
| Sequence (5′–3′) | ACGAGTCTTCGGTTTCCTCAG | GATTATGATTCCACTGTACGGACG |
| Length | 21 bp | 24 bp |
| Position | 156–176 | 693–716 |
| Tm | 59.73°C | 59.32°C |
| GC Content | 52.38% | 45.83% |

**Predicted amplicon size: 561 bp**

## Analysis Performed

1. Retrieval of the CBF3 mRNA sequence from NCBI GenBank.
2. Identification of the coding sequence using ApE.
3. Selection of forward and reverse primers.
4. Primer evaluation using NCBI Primer-BLAST.
5. Analysis of primer length, melting temperature and GC content.
6. Specificity assessment against the selected database.
7. Secondary-structure analysis using IDT OligoAnalyzer, including hairpin, self-dimer and heterodimer formation.

## Key Findings

- The forward and reverse primers showed comparable melting temperatures, with a difference of 0.41°C.
- Both primers had GC content within the commonly used 40–60% range.
- Primer-BLAST predicted an amplification product of 561 bp.
- No additional targets were detected in the selected database under the search conditions used.
- The predicted secondary-structure interactions were relatively weak.

## Limitations

- The results are based on computational predictions.
- Primer specificity depends on the database and search parameters.
- Secondary-structure predictions do not confirm actual PCR performance.
- Experimental PCR and sequencing validation have not been performed.

## Future Scope

The selected primer pair can be further evaluated through experimental PCR using suitable cDNA as the template. The amplified product can be analysed by agarose gel electrophoresis and verified through sequencing.

## Project Report

The complete report, including graphical results, screenshots, interpretations and references, is available in the PDF uploaded to this repository.

**File:** `CBF3_Primer_Design_Report.pdf`

## References

1. Gilmour et al. (1998). Low temperature regulation of the Arabidopsis CBF family of AP2 transcriptional activators. *The Plant Journal*, 16(4), 433–442.
2. Liu et al. (1998). Two transcription factors, DREB1 and DREB2, with an EREBP/AP2 DNA binding domain. *The Plant Cell*, 10(8), 1391–1406.
3. NCBI GenBank. CBF3 mRNA, accession AF074602.1.
4. NCBI Primer-BLAST.
5. Integrated DNA Technologies (IDT). OligoAnalyzer.
