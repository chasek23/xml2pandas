# xml2pandas

##### Creator: Chase Kelly
##### Last Updated: 7/2019

This package is intended to turn 2-D data in `.xml` format into a pandas DataFrame.

### Installation:

`pip install xml2pandas`

### Use:

- `from xml2pandas import ReadXML`
- `xml = ReadXML('/path/to/file.xml')`
- `xml()` - preserving call for inevitable keywords and options
    - `xml(detect=True)` will convert numeric colum
- `df = xml.df`


