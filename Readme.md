Google-Autocomplete-analysis
============================

Script and data in this repository are for scraping responses of [Google Autocomplete](https://support.google.com/websearch/answer/106230?hl=en) to questions of the form **_why is &lt;country x&gt; so_**.

Methodology
-----------
The data file is based on data from [Natural Earth](http://www.naturalearthdata.com). Additional flags for plural and definite form were added, thus the script handles adjustments such as the following automatically:

* **_why is the Central African Republic so:_** definite article
* **_why are The Bahamas so:_** plural, the definite article is part of the official name
* **_why are the Philippines so:_** plural and definite article

Further, the data file contains various naming variants for the *United States of America* as well as for the *United Kingdom* (for the latter, *Great Britain* was also included, despite these not being identical).

Context
-------

This script has been employed for assembling the input data to [_The World through the Eyes of a Search Algorithm_](http://geography.oii.ox.ac.uk/#the-world-through-the-eyes-of-a-search-algorithm) on the [_Information Geographies_ blog](http://geography.oii.ox.ac.uk) of the [Oxford Internet Institute](http://www.oii.ox.ac.uk) at the University of Oxford.

![Happy and powerful countries according to Google Autocomplete](http://geography.oii.ox.ac.uk/wp-content/uploads/2014/01/happy_powerful-1024x724.png)

