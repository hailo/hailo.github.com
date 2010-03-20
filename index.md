---
title: A pluggable Markov engine analogous to MegaHAL
layout: default
---

# Welcome to Hailo

Hailo is a a pluggable Markov engine intended to be a fast and
scalable replacement for
[MegaHAL](http://megahal.alioth.debian.org/). Hailo is written in Perl
and uses a RDBMS ([SQLite](http://www.sqlite.org/),
[PostgreSQL](http://www.postgresql.org/) or
[MySQL](http://www.mysql.com/)) as a backend to store its brain.

Unlike MegaHAL it can handle brains of arbitrary size (whatever your
RDBMS can take), properly supports learning in any Unicode language
and generates replies in a fraction of the time MegaHAL does.

Hailo can be used either as a Perl module or via the `hailo`
command-line interface. See [the main
documentation](http://search.cpan.org/dist/Hailo/lib/Hailo.pm) for
more information.

## Installing

Hailo is packaged on the [CPAN](http://search.cpan.org/). If you're
unfamiliar with using the CPAN the easiest way to install Hailo is
with
[cpanminus](http://search.cpan.org/dist/App-cpanminus/lib/App/cpanminus.pm),
for example:

    sudo wget http://bit.ly/cpanm -O /usr/local/bin/cpanm
    sudo chmod +x /usr/local/bin/cpanm
    sudo cpanm Hailo

## Links

 * The [Hailo project](http://github.com/hailo) on GitHub
 * The [documentation for Hailo](http://search.cpan.org/dist/Hailo/lib/Hailo.pm) on the CPAN
 * The [SEE ALSO section](http://search.cpan.org/dist/Hailo/lib/Hailo.pm#SEE_ALSO) in Hailo's documentation
 * [Blogs about Hailo](http://blogs.perl.org/users/aevar_arnfjor_bjarmason/hailo/) by Ævar Arnfjörð Bjarmason
