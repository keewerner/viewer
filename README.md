# viewer

## Description

Simple IIIF viewer based on Mirador Latest with paramaters snatched from URL.

### Parameters

| parameter | options                                |                               |
| --------- | -------------------------------------- | ----------------------------- |
| manifest  | [URL]                                  | a valid manifest v2 or v3     |
| canvas    | [0-9]* without leading zeroes          | 124 is ok, but not 009        |
| view      | annotations, attribution, canvas, info | for now, not search or layers |

### Example

```
https://keewerner.github.io/viewer/?manifest=https://dlib.biblhertz.it/iiif/dm5055800/manifest2.json&view=annotations&canvas=17
```
