# Mission Information Local Data Dictionary (LDD)

The Mission Information Dictionary contains classes, attributes, and rules for specifying generic metadata elements which are common among mission observations (as opposed to other types of observations).

Steward: [IMG Node](https://pds-imaging.jpl.nasa.gov/)

## Current Source

Only one LDD source version is kept such that it can be managed by github.

- [src](src)

## Versions

A Local Data Dictionary (LDD) is built for selected versions of the [PDS4 Information Model](https://pds.nasa.gov/pds4/doc/im/).
The build process insures compatibility of the LDD with the core information model.

## Builds

This LDD has been built for the following versions:

- [builds](build)

## Tagged Releases

- [releases}(releases)

## Notes

Each build is generated using the [lddtool](https://pds.nasa.gov/tools/about/ldd/) specific to a version of the [PDS4 Information Model](https://pds.nasa.gov/datastandards/documents/im/). The build command used is:

```
lddtool -lpsnJ ldd-file.xml
```


# Contribute

Have a bug or feature request? Create one in the [PDS4 Issue Repo](https://github.com/pds-data-dictionaries/PDS4-LDD-Issue-Repo/issues/new/choose).


# Support

See the [PDS Data Dictionaries Support page](https://pds-data-dictionaries.github.io/support/) for more Support information.
