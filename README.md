# HMOX1 Phylogenetic Analysis

I've been interested in bioinformatics for a while, and when my advisor suggested HMOX1 as a thesis topic, I decided to build a proper phylogenetic analysis around it. The gene itself is involved in oxidative stress response  pretty conserved across vertebrates, which makes it a good candidate for this kind of comparative work.

The species selection was mine to figure out. I ended up including axolotl (*Ambystoma mexicanum*) because salamanders genuinely fascinate me — their regeneration capacity is unlike almost anything else in vertebrates, and I wanted to see where HMOX1 sits in that lineage relative to other amphibians.

## What I did

Pulled 50 nucleotide sequences from NCBI, ran a MUSCLE alignment in MEGA12, then built a Neighbor-Joining tree with 1,000 bootstrap replicates. Final alignment came out to 357 positions after gap handling.

The taxa cover mammals, birds, reptiles, amphibians, and fish  including some less common picks like coelacanth (*Latimeria chalumnae*) and a few turtle species.

## What came out

- Teleost fish show two paralogous HMOX1 copies (turA / turB), which lines up with the teleost whole-genome duplication
- Mammals and birds cluster tightly, consistent with strong conservation under purifying selection
- Axolotl groups with other urodeles as expected, but the branch lengths within amphibians are interesting
- Coelacanth sits where you'd expect — outgroup to tetrapods, closer to fish than to land vertebrates

## Files

- `Yeni_Nükleo_Diziler.mas` — raw sequences
- `Yeni_Nükleo_Diziler_muscle_alignment.mas` — MUSCLE alignment
- `Yeni_Nükleo_Diziler_Ağaç.mtsx` — phylogenetic tree (open with MEGA12)

## Tools

MEGA12, NCBI Nucleotide

---

Görkem Benli — Bioengineering, Bursa Technical University  
[LinkedIn](https://www.linkedin.com/in/görkem-benli-8b54a8246/)
