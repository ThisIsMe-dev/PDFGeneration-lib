# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.0.1] - 2020-07-17

### POC

- This is the library in a POC state.

## [1.0.0] - 2020-07-25

### Initial Release

- This library is now being used by ThisIsMe's Company Credit Report v3 call.

## [2.0.0] - 2020-07-30

### The Clean Release

- Previous code base was unstable and heading down a spaghetti code path, a lot of refactoring was done to avoid unnecessary errors and confusion, this version also supports more line types.
- Library name also changed from `@ThisIsMe/pdfgeneration-lib` to `@thisisme/pdfgeneration-lib`.

## [3.0.0] - 2020-08-10

### The Fancy Release

- Text have been made smaller.
- Fancy headers have been brought in for defined Headers.
- Grid Type has been added.
- File Structure has been improved, not just using app.js but split logic into different files as welll to help improve readability and maintainability.
- Pipelines have been implemented to test code pushed up.

## [4.0.0] - 2020-08-29

### The start of document types

- Document types added.
- More line types added.
- Helper builders added.

## [4.0.1] - 2020-08-30

### Bug fix

- width size of rows on pdf reduced to prevent lines going over to next.

## [5.0.0] - 2020-10-08

### Image and Indicative Bar (Score)

- Some refactoring to ease reading and future maintainability
- New types

## [5.0.1] - 2020-10-11

### Bug fix

- Minor logging corrections

## [5.1.1] - 2020-10-16

### Minor change

- Report bucket setting changed env var

## [5.2.1] - 2020-10-16

### Minor change

- AWS_DEFAULT_REGION reference changed to TIM_AWS_DEFAULT_REGION

## [5.3.0] - 2020-11-04

### Cover Page & Bug fixes

- Code restructure
- Cover Page added as a PDF Type
- Fixed headers that aren't selected as new page headers
- Fixed async issue with older PDF Types
- Added functionality to build tables

## [5.3.1] - 2020-11-05

### Bug fix

- splitLongText function fixed, was not catering for long words

## [5.4.0] - 2020-11-08

### Image functionality improvements and Grid font selection

- images will be placed side by side when array of images
- custom font adjustments specifically for Grid types

## [5.5.0] - 2020-11-17

### Image functionality improvements

- Image types added (Default and Center)
- Center adds image in the center of the focused line
- Helper functions added for image creation
- Fixed some camel case occurrences

## [5.6.4] - 2021-02-21

### Bug fix

- Bug fix, "bwip-js": "2.0.12" introduces an `undefined` value bug, locking version to 2.0.11.

## [5.6.5] - 2021-03-02

## Allow front page with Search Params

- allow front page without search params | checks null state

## [5.6.6] - 2021-03-02

## Allow front page with Search Params - Fix for 5.64

- allow front page without search params | checks object length

## [5.7.0] - 2021-03-4

## Image descriptions

- y increments for images fixed, extending base pdfkit
- Single images now cater for descriptions
- Centered fixed
- Image code refactor

## [5.8.0] - 2021-04-14

## Pdf responds when upload complete

- The PDF location will now be received when upload to s3 was successful

## [5.9.0] - 2021-04-14

## QRCode generation fix | Unit tests added

- `Jest` added for unit tests
- `'use strict'` above all .js files
- QRCode generation function fixed, covered by unit test

## [5.10.0] - 2021-04-21

## imageDescriptions support for addImageLineFromBase64 

- added imageDescriptions support to addImageLineFromBase64 
- re-ordered the import modules to match external, internal flow

## [5.10.1] - 2021-06-19

## Removed QRCode generation