# Generic Mission Local Data Dictionary (LDD)

The generic Mission Dictionary contains classes, attributes, and rules for specifying metadata elements which are common among mission observations (as opposed to other types of observations).

Steward: [IMG Node](https://pds-imaging.jpl.nasa.gov/)

## Released Versions

A Local Data Dictionary (LDD) is built for each version of the [PDS4 Information Model](https://pds.nasa.gov/datastandards/documents/im/).
The build process ensures compatibility of the LDD with the core information model.

This LDD has been released for the following versions of the PDS4 information model:

- [PDS4 IM v1.9.0.0 (MSN LDD v0.1.9.0)](https://github.com/nasa-pds-data-dictionaries/ldd-msn/releases/tag/v0.1.9.0)
- [PDS4 IM v1.7.0.0 (MSN LDD v0.1.7.0)](https://github.com/nasa-pds-data-dictionaries/ldd-msn/releases/tag/v0.1.7.0)


## Notes

Each build is generated using the [lddtool](https://pds.nasa.gov/tools/about/ldd/) specific to a version of the [PDS4 Information Model](https://pds.nasa.gov/datastandards/documents/im/). The build command used is:

```
lddtool -lpsnJ ldd-file.xml
```
