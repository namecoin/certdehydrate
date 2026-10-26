certdehydrate
=============

certdehydrate is a library that can compress ("dehydrate") X.509 certificates that follow a known template. It can then decompress ("rehydrate") the certificate by filling in the template. This yields significant space savings, and also gives some security guarantees if the template is known to be safe (e.g. having the CA bit cleared).

Namecoin used certdehydrate for many years. We no longer use it, because we found other approaches that save even more space, and which have even stronger security guarantees. Those other approaches may or may not work for your use cases. This library is unmaintained, and is published because it's academically and historically interesting, not because we expect you to use it. Perhaps it will inspire you to do something cool.

If you have questions about certdehydrate, please feel free to reach out. We're always happy to talk to fellow researchers.

Licence
-------

Licenced under the GPLv3 or later.
© 2015-2026 Namecoin Developers.
