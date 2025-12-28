---
name: New Strain Registration
about: Propose adding a new microbial or fungal strain to the registry
title: "[New Strain] "
labels: ["strain-registration"]
assignees: []
---

## Strain Information

**Strain Name:** (e.g., *Lactococcus lactis* subsp. *cremoris* strain IMC-C01)

**Source Cheese:** (e.g., A sample of Pont-l'Évêque)

**Isolation Date:** (YYYY-MM-DD)

**Key Growth Characteristics:**
- Temperature range: (e.g., 20-30°C)
- Optimal pH: (e.g., 5.5-6.5)
- Aerobic/Anaerobic: (e.g., Facultative anaerobic)
- Medium preference: (e.g., MRS agar)
- Other notable traits: (e.g., Slow growth, produces yellow pigment)

**Sequencing Information:**
- 16S rRNA or ITS GenBank Accession Number: (if available)
- Sequencing method: (e.g., Illumina MiSeq, PacBio)
- Coverage/depth: (e.g., 50x)
- Link to raw data: (optional)

**Notes on Interactions:**
- Observed interactions with other microbes/fungi: (e.g., "Observed to inhibit growth of *Geotrichum candidum* on agar plates.")
- Known antagonistic or synergistic relationships:
- Production of antifungal/antibacterial compounds:

**Additional Metadata:**
- Collector/Lab: (e.g., IMC Lab, Jane Doe)
- Storage location: (e.g., -80°C freezer, box #3)
- Viability status: (e.g., Active, cryopreserved)

## Checklist

- [ ] Strain name follows naming convention (Genus species strain ID)
- [ ] All required fields filled
- [ ] Growth characteristics verified by lab experiments
- [ ] Sequencing data submitted to public repository (if applicable)
- [ ] Interaction notes based on observed experiments
- [ ] File prepared in `strains/` directory with appropriate naming

**After submission:** Please create a pull request linking this issue, adding the strain file to the `strains/` directory.