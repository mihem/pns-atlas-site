---
# Leave the homepage title empty to use the site title
title:
date: 2024-12-12
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
        This is the corresponding website to the publication [Multi-omic characterization of human sural nerves across polyneuropathies](https://www.biorxiv.org/content/10.1101/2024.12.05.627043v1).

        We present a large scale single cell transcriptional and spatial atlas of human peripheral nerves in health and disease (polyneuropathies).
        Interactive visualizations of the single nuclei sural nerve dataset and the spatial transcriptomics data (Xenium) can be found below.

        The code used for the analysis can be found on [GitHub](https://github.com/mihem/sural_atlas).
        The raw sequencing will be available in [GEO](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE) soon.

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

  - block: contact
    id: contact
    content:
      title: Contact
      text:
      email: gerd.mzh@uni-muenster.de
      address:
        street: Albert-Schweitzer-Campus 1
        city: Münster
        postcode: '48149'
        country: Germany
        country_code: DE
      coordinates:
        latitude: '51.96100'
        longitude: '7.59479'
      contact_links:
       - icon: twitter
         icon_pack: fab
         name: Follow us on Twitter
         link: 'https://twitter.com/mzhlab'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '1'

---