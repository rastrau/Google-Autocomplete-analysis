google_autocomplete
===================

Script and data in this repository are for scraping responses of [Google Autocomplete](https://support.google.com/websearch/answer/106230?hl=en) to questions of the form **_why is &lt;country x&gt; so_**.

The data file is based on data from [Natural Earth](http://www.naturalearthdata.com). Additional flags for plural and definite form were added, thus the script handles adjustments such as the following automatically:

* **_why is the Central African Republic so:_** definite article
* **_why are The Bahamas so:_** plural, the definite article is part of the official name
* **_why are the Philippines so:_** plural and definite article

Further, the data file contains various naming variants for the *United States of America* as well as for the *United Kingdom* (for the latter, *Great Britain* was also included, despite these not being identical).
