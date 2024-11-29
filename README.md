# Text Lists for the Internet Storm Center (ISC) API
> IMPORTANT: This repository and distribution of ISC data is completely unofficial. I am not associated with them in any way.

# Why does this exist?
The [Internet Storm Center API](https://isc.sans.edu/api/) has plain text as an output option, but it isn't the right format expected by OPNsense and probably a lot of other firewalls. The scripts in this repository create compatible plain text lists directly from the JSON data (which is easier to parse).

# How do I use this?
> GitHub Actions has not been set up yet, so these instructions don't actually work at the moment.

You can select a list from the [latest GitHub release](https://github.com/anon-123456789/isc-text-lists/releases). The links there always point to the latest version, so they will update automatically in your firewall.
# License
__This repository and the generated list files (in GitHub releases) have completely different licenses.__
Full license text can be found in LICENSE.md.

### Repository code
This repository is licensed under the [GNU GPL, version 3](https://www.gnu.org/licenses/gpl-3.0-standalone.html).
```
isc-text-lists, a project by anon-123456789
Copyright (C) 2024 anon-123456789
    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.
```

### Generated list files
The generated lists are licensed under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/), as the original data uses that license. Due to incompatibilities with the GPLv3 (among other reasons), generated lists are only available in GitHub releases.