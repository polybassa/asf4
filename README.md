# asf4
Microchip/Atmel ASF4 code libraries

http://start.atmel.com is the way to access the ASF4 code libraries from Microchip. It is a code selection tool: you specify the libraries you need and some parameters, and then you download a package of code for your selected chip and application.

Since we need to support multiple chips and use a large chunk of the library, the scheme above is awkward, and it's difficult to update cleanly.

This repo contains a code tree of a large selection of ASF4 code, downloaded for both SAMD21 and SAMD51 (and more chips later).

# Branches

## Master Branch
Branch `master` contains the code as downloaded. It should be updated periodically. As of this writing there is no way to know when the code is updated on the website, so we must check periodically.

## Bugfix Branch
Branch `master-bugfixes` is a branch from `master` that contains bugfixes needed by potentially all users of ASF4.

## Project Branches
These branches contain enhancements for specific Adafruit projects and families of products.

* `circuitpython` - Changes needed for https://github.com/adafruit/circuitpython

# Tools
`tools/` contains scripts that are useful for updating and organizing the code trees.