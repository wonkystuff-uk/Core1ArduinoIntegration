# Board support for Wonkystuff Core1 Rev.D

First version: Basic integration with Arduino IDE 1.8.13. Test application
has been built and `hex2wav.jar` seen to run and create audio.

`variants` and `cores` directories have been thinned out; `avrdude` and `bootloaders`
directory have been removed since this integration is only intended to support the upload
of code via audio.

**`libraries` was mostly links to other repos, so this has also been emptied -- it might be
nice to add the examples at some point**
