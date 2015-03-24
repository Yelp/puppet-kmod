# Kmod Puppet module

[![Puppet Forge Version](http://img.shields.io/puppetforge/v/camptocamp/kmod.svg)](https://forge.puppetlabs.com/camptocamp/kmod)
[![Puppet Forge Downloads](http://img.shields.io/puppetforge/dt/camptocamp/kmod.svg)](https://forge.puppetlabs.com/camptocamp/kmod)
[![Build Status](https://img.shields.io/travis/camptocamp/puppet-kmod/master.svg)](https://travis-ci.org/camptocamp/puppet-kmod)
[![Puppet Forge Endorsement](https://img.shields.io/puppetforge/e/camptocamp/kmod.svg)](https://forge.puppetlabs.com/camptocamp/kmod)
[![Gemnasium](https://img.shields.io/gemnasium/camptocamp/puppet-kmod.svg)](https://gemnasium.com/camptocamp/puppet-kmod)
[![By Camptocamp](https://img.shields.io/badge/by-camptocamp-fb7047.svg)](http://www.camptocamp.com)

## Usage

See inline doc inside:

  * kmod::load
  * kmod::alias
  * kmod::install
  * kmod::blacklist

## Description

This module provides definitions to manipulate modprobe.conf (5) stanzas:

 * kmod::alias
 * kmod::install
 * kmod::blacklist

It depends on Augeas with the modprobe lens.

## Contributing

Please report bugs and feature request using [GitHub issue
tracker](https://github.com/camptocamp/puppet-kmod/issues).

For pull requests, it is very much appreciated to check your Puppet manifest
with [puppet-lint](https://github.com/camptocamp/puppet-kmod/issues) to follow the recommended Puppet style guidelines from the
[Puppet Labs style guide](http://docs.puppetlabs.com/guides/style_guide.html).

## License

Copyright (c) 2013 <mailto:puppet@camptocamp.com> All rights reserved.

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.
    
    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.
    
    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

