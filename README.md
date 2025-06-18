[![Actions Status](https://github.com/Raku-L10N/FR/actions/workflows/linux.yml/badge.svg)](https://github.com/Raku-L10N/FR/actions) [![Actions Status](https://github.com/Raku-L10N/FR/actions/workflows/macos.yml/badge.svg)](https://github.com/Raku-L10N/FR/actions) [![Actions Status](https://github.com/Raku-L10N/FR/actions/workflows/windows.yml/badge.svg)](https://github.com/Raku-L10N/FR/actions)

NAME
====

L10N::FR - French localization of Raku

SYNOPSIS
========

    $ freku -e 'dis "Bonjour Monde"'
    Bonjour Monde

```raku
use L10N::FR;
dis "Bonjour Monde";
```

DESCRIPTION
===========

The `L10N::FR` distribution contains the logic to provide a French localization of the Raku Programming Language. It installs a `nedku` executable that will automatically activate the French localization. And it allows one to use the French localization in selected programs with a `use L10N::FR` statement.

AUTHORS
=======

Lucien Grondin

COPYRIGHT AND LICENSE
=====================

Copyright 2023, 2025 Raku Localization Team

This library is free software; you can redistribute it and/or modify it under the Artistic License 2.0.

