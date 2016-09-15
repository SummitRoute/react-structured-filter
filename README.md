
# react-structured-filter (unmaintained)
react-structured-filter is a javascript library that provides autocomplete faceted search queries.  
This was inspired by [visualsearch](http://documentcloud.github.io/visualsearch) and
[structured-filter](https://github.com/evoluteur/structured-filter) but redone for
[React](http://facebook.github.io/react/).

It is heavily based on [react-typeahead](https://github.com/fmoo/react-typeahead) and uses some modified code from
[react-datepicker](https://github.com/Hacker0x01/react-datepicker).  
It was developed to be used with [Griddle](http://dynamictyped.github.io/Griddle/),
but should be usable with [fixed-data-table](https://github.com/facebook/fixed-data-table).

It is used by [Summit Route](https://summitroute.com/) internally for analyzing our data.  
We needed an interface to provide advanced querying capabilities.
Be aware that it might be confusing to your users and queries can be constructed that may not be performant on your dataset.

The demo provided uses static data sent down to the client.  
You should poll data from a server and do filtering on a real database.

## Demo
Check out the [docs](http://summitroute.github.io/react-structured-filter/) and [demo](http://summitroute.github.io/react-structured-filter/demo.html)

### License
BSD License
