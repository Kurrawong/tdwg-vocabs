# TDWG Vocabularies

This repository contains the source data files for Biodiversity Information Standards (TDWG)'s vocabularies.

These vocabularies contain controlled terms important for TDWG's work.


## Content

The vocabularies will shortly be published online with details to be added here then.

The individual vocabulary files are stored in the `resources/vocabularies/` folder.

Alongside the vocabularies' content are a series of supporting assets that allow this collection of vocabularies to operate under the [PrezManifest](https://prez.dev/prezmanifest) Knowledge Graph content synchronisation system. The critical resources are the manifest file (`resources/manifest.ttl`) and the catalogue (`resources/catalogue.ttl`). The former points to all content - vocabularies, the catalogue and background labels - to allow for automated synchronisation of this repository with a publication system's Knowledge Graph database. The latter provides the human- and machine-readable logical listing of the vocabularies as a catalogue in the publication system.

### Content Sources

Where vocabularies have been developed using [VocExcel](https://pypi.org/project/vocexcel) authoring templates, the Excel files are stored in the `sources/` folder with the same first part of the file name as their resulting RDF vocabularies files in the `resources/vocabularies/` folder.

## Contact

Please contact TDWG on https://www.tdwg.org/about/contact/ for all issues relating to these resources.
