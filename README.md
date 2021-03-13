# Alien::castxml ![linux](https://github.com/PerlFFI/Alien-castxml/workflows/linux/badge.svg) ![macos](https://github.com/PerlFFI/Alien-castxml/workflows/macos/badge.svg)

Find or build castxml

# SYNOPSIS

In your script or module:

```perl
use Alien::castxml;
use Env qw( @PATH );

unshift @PATH, Alien::castxml->bin_dir;
```

# DESCRIPTION

This distribution provides castxml so that it can be used by other
Perl distributions that are on CPAN.  It does this by first trying to
detect an existing install of castxml on your system.  If found it
will use that.  If it cannot be found, the source code will be downloaded
from the internet and it will be installed in a private share location
for the use of other modules.

# SEE ALSO

[Alien](https://metacpan.org/pod/Alien), [Alien::Base](https://metacpan.org/pod/Alien::Base), [Alien::Build::Manual::AlienUser](https://metacpan.org/pod/Alien::Build::Manual::AlienUser)

# AUTHOR

Graham Ollis <plicease@cpan.org>

# COPYRIGHT AND LICENSE

This software is copyright (c) 2020 by Graham Ollis.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
