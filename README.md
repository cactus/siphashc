siphashc
========

## Current status of project

Ongoing maintenance of the project (and pypi package) has transferred to Michal
Čihař ([nijel][4]).  
[WeblateOrg/siphashc][5] is now the canonical location.


### Introduction

siphashc is a python2 c-module for [siphash][1], based on [floodberry's
version][2].


### Usage

~~~ python
>>> from siphashc import siphash
>>> siphash('sixteencharstrng', 'i need a hash of this')
10796923698683394048L
~~~

### License

Released under the [ISC license][3]. See `LICENSE.md` file for details.

[1]: https://131002.net/siphash/
[2]: https://github.com/floodyberry/siphash
[3]: https://choosealicense.com/licenses/isc/
[4]: https://github.com/nijel
[5]: https://github.com/WeblateOrg/siphashc
