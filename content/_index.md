---
# Leave the homepage title empty to use the site title
title:
date: 2025-08-23
type: landing

sections:
  - block: hero
    content:
      title: Welcome to the <br> Human PNS Atlas
      image:
        filename: scheme_manuscript.jpg
      text:

  - block: markdown
    content:
      title:
      text: |
        This is the corresponding website to the publication [Multi-omic characterization of human sural nerves across polyneuropathies](https://doi.org/10.1038/s41467-025-62964-8) by Heming et al, *Nature Communications*,  August 2025.

        We present a large scale single cell transcriptional and spatial atlas of human peripheral nerves in health and disease (polyneuropathies).
        Interactive visualizations of the single nuclei sural nerve dataset and the spatial transcriptomics data (Xenium) can be found below.

        The code used for the analysis can be found on [GitHub](https://github.com/mihem/sural_atlas) and has been archived on (Zenodo)[https://zenodo.org/records/15750104].
        The raw sequencing is be available in GEO [GSE285983](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE285983) and [GSE285984](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE285984).
        To reproduce the figures, we created a [Quarto document](https://mihem.github.io/pns_atlas/), which automatically downloads all relevant data from *Zenodo*.

  - block: collection
    id: datasets
    content:
      title: Datasets
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: datasets
    design:
      view: showcase
      columns: '1'
      flip_alt_rows: false

  - block: markdown
    id: contact
    content:
      title: Contact
      text: |
        If you have any questions, please contact us via [mheming.com](https://www.mheming.com).
---