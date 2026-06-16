# ncas-data-instrument-vocabs
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10169854.svg)](https://doi.org/10.5281/zenodo.10169854)

Controlled vocabulary of instruments as part of NCAS Data Activity

Repository is linked to Zenodo for tagged releases of this vocabulary.


### Guiding principles for instrument identifiers

 - First part designates the organisation (e.g. ncas-)
 - Avoid using manufacturer names
 - Focus instread on instrument type
 - And 'point-of-interest' for the instrument's operations
 - Try to be consistent with similar instruments (agnostic of manufacturers or models)
 - Add in a sequential number

e.g.

 `ncas-<type-of-instrument>-<point-of-interest>-X`

### Definitions
Instrument: free text shorthand name relating to the instrument
Manufacturer: free text name of instrument manufacturer
Model No.: free text model number/identifier of the instrument
Serial Number: free text serial number specific to the instrument
Old Instrument Name: previous used identifier(s) for the instrument
New Instrument Name: currently used identifier for the instrument
Data Product(s): NCAS standard defined data products that the instrument may produce
Mobile/Fixed (loc): indicator of the observatory with which the instrument is affiliated - "Mobile" or "fixed - <observatory name>"
Legal Owner: the actual legal entity that owns the instrument
Scientist: name of the scientist responsible for operation of instrument
Category: broad category of instrument type
Descriptor: long form of the "New Instrument Name"
Administrating Body: body determining the instrument's operational use (for example NCAS or AMOF)
