google_autocomplete
===================

Script and data in this repository are for scraping responses of Google Autocomplete to questions of the form 'why is <country x> so'.

The data file is based on data from [Natural Earth](http://www.naturalearthdata.com). Additional flags for plural and definite form were added, thus the script handles adjustments such as the following automatically:

* 'why is the Central African Republic so' (definite article)
* 'why are The Bahamas so' (plural; definite article is part of the official name)
* 'why are the Philippines so' (plural and definite article)

Further, the data file contains various naming variants for the United States of America as well as for the United Kingdom(for the latter, 'Great Britain' was also included, despite these not being identical).
