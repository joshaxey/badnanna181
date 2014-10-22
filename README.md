badnanna181
===========

Beginning of a webkit vuln repro reduction for Vita FW 1.81 and lower. Shelved.

Takes advantage of an issue in dtoa.cpp allowing us to specify an external non-standard NaN for parsing, it is not properly validated and crashes.

Vita target is 1.81 and lower.

Beginning of reduction attempt, want to call this "Bad Nanna" once I had worked out payload and adapted to work with dumper.
Became 'irrelevant' once work began on higher firmware version. Others have also taken advantage of this privately and I assume will release soon.
