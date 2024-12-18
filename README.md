# Project 31: Executable metadata mappings to FAIRify Biodiversity Genome Annotations

## Main goals

The [FAIRification of Genomic Annotations Working Group (FGA-WG)](https://www.rd-alliance.org/groups/fairification-genomic-annotations-wg/) in the Research Data Alliance will focus on the challenges of harmonising metadata and software solutions to improve the discovery and reuse of publicly available genomic annotation data.

Our Biohackathon project aims to:

- Define minimal metadata to support genome annotations as FAIR objects, and
- Develop interoperable executable mappings from bioinformatics case-studies to the [FAIRtracks model](https://github.com/fairtracks/fairtracks_standard#overview-of-structure-of-the-fairtracks-standard).

Our PLAN during the biohackathon is to assess and implement the following:

- What research data / metadata do we have that we can use as a case study?
- What do we want in terms of interoperability, and will the Fairtracks schema provide sufficient coverage for the source metadata in our case-study?
- What definitions are missing, or what level of lossiness is "acceptable"? How do we document this loss?
- What tools and processes are needed to algorithmically produce a transformation?
- Review [Omnipy](https://omnipy.readthedocs.io/) / [Whyqd (/wɪkɪd/)](https://whyqd.readthedocs.io/) (two Python-based libraries for data wrangling) to algorithmically produce a transformation. 

## Interested in contributing?

We have a diverse group of people participating, both on-site and remotely - including collaborators calling in from Australia - and we would appreciate people with any of the following skills or resources to contribute:

- Schema.org / bioschemas familiarity (or metadata for research annotations)
- Metadata modelling for interoperability
- Bioinformatics research data / metadata to contribute as case-studies for transformation
- Python & JSON / JSON-LD

:loudspeaker: Get hold of us:

- [Biohackathon slack community](https://biohackeu.slack.com/archives/C07MS890N6S): **Sveinung Gundersen**
- Co-lead emails:
  - [**Gavin Chait**](mailto:gchait@whythawk.com)
  - [**Sveinung Gundersen**](mailto:sveinugu@uio.no)

Our project is committed to inclusivity, guided by the [ELIXIR code of conduct for events](https://elixir-europe.org/events/code-of-conduct) and the [ELIXIR RSEc code of conduct](https://github.com/research-software-ecosystem/content/blob/master/CODE_OF_CONDUCT.md). We value inputs from a multitude of perspectives, levels of experience and skill, and across a diversity of professional, personal, cultural, or linguistic backgrounds.

Remote participation is welcome, and we are supporting cross-over time-zones for our Australian contributors. Expect us online from about 7am CET from Tuesday, 6 November.

## Resources

- [Current list of remote and on-site contributors](https://docs.google.com/spreadsheets/d/10wO-5kNdaTUpsZ3C0z5bsaYnf5EbDAWPw86wTmeHPkI/edit?gid=946925182#gid=946925182)
- [Resource reading list](https://docs.google.com/spreadsheets/d/10wO-5kNdaTUpsZ3C0z5bsaYnf5EbDAWPw86wTmeHPkI/edit?gid=750772179#gid=750772179)
- [Potential genome annotation metadata case-studies](https://docs.google.com/spreadsheets/d/10wO-5kNdaTUpsZ3C0z5bsaYnf5EbDAWPw86wTmeHPkI/edit?gid=0#gid=0)
- [Rolling collaboration notes](https://docs.google.com/document/d/1xT-45UgIp-ujkudaN589RgJdvib3vVj_N4L9SQAgltw/edit?usp=sharing)

## Abstract

Advances in sequencing technologies and assembly algorithms have enabled an explosion in diverse reference genomes across the tree of life, together with a need to annotate functional and structural features. There is no current set of minimal metadata to support genome annotations as FAIR objects, limiting their reproducibility and reliability.

The FAIRification of Genomic Annotations Working Group (FGA-WG) in the Research Data Alliance (RDA) will develop a harmonised metadata model and recommended infrastructure to improve discovery and reuse of publicly available genomic annotations/tracks, supporting harmonised metadata for GFF3 files. Such metadata exists in e.g. project-specific databases or spreadsheets, workflow systems, repositories, exchange formats, and linked data.

Harmonising metadata according to a unified data model requires the extraction, transformation and integration of data sourced in different research contexts, including "messy" data, using schema mappings or "crosswalks". These operations are time-consuming and may introduce opaque errors. FAIR principles emphasise reproducibility and trust in data analyses with persisted and shared accessible, auditable and executable data transformation and validation methods.

[Omnipy](https://omnipy.readthedocs.io/) and [Whyqd (/wɪkɪd/)](https://whyqd.readthedocs.io/) are independently-developed Python libraries offering general functionality for auditable and executable metadata mappings. Each is pragmatically designed to ensure transformations are executable on real-world data, with validation and feedback. They differ in scope and users, and provide complementary functionalities.

In this project, we will integrate Omnipy and Whyqd to develop executable mappings that transform existing metadata from biodiversity projects, such as ERGA, to conform to the FGA-WG metadata model, kickstarting the process of FAIRifying genome annotation GFF3 files.

## Lead(s)

Sveinung Gundersen ɴᴏ, Gavin Chait ᴢᴀ
