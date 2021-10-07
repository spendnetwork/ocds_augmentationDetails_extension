# ocds_augmentationDetails_extension

A detailed extension to describe any modified or generated fields. This includes metadata around them such as the generation method and measure of confidence.
This is currently set up to either flag fields within the same release which have been modified, using JSONPath to indicate the location, or to reference an external document by OCID which could be related. 
Use cases here could be flagging possible duplicates of the same document published across different sources, or indicating possible connections between different phases of procurement which are published across different sources.


## Guidance


## Example

```json

```

## Issues

Report issues for this extension in the [ocds-extensions repository](https://github.com/open-contracting/ocds-extensions/issues), putting the extension's name in the issue's title.

## Changelog

### 2021-10-01

* Initial commit
