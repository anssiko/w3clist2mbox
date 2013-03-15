w3clist2mbox
============

NAME

w3clist2mbox - Convert a W3C-style hypermail mail archive referenced by an URL
to a Unix mbox file.

SYNOPSIS

Downloads a W3C-style hypermail archive referenced by 'url', and converts
it to a Unix mbox file.
  
  w3clist2mbox url
  
DESCRIPTION

This script automates the process of converting a W3C-style hypermail archive
to a Unix mbox file, to be imported into your email client, for example. The
conversion is handled by hm2mbox-w3c, which is a patched version of hm2mbox to
support W3C-style archives.

See hm2mbox <http://www.tifaware.com/perl/hm2mbox/> for required Perl modules.

COPYRIGHT AND LICENSE

Copyright (c) 2013, Anssi Kostiainen.
All rights reserved.

This script is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.
