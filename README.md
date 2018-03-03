# Preface
This is a minimal Debian packaging project that creates `systemd` service. Replace all `_UPPERCASE_` style tags with appropriate messages before making a release! Remove this `Preface` section to have a clean readme file.

To build the package:
1. Release the changelog file using `dch --release` command. Commit the changes to repository.
2. For testing, run `dpkg-buildpackage -uc -us` to avoid any PGP signing.
3. For final release, run `dpkg-buildpackage` without any arguments. Sign source and changes artifacts with PGP key.
4. Publish the package to a website or APT repository (process not covered here).

# About This Project

# Installation
Please visit http://pkg.baltnet.net for instructions how to configure Baltnet repository and install this package.

# Configuration
There is no default working configuration which a daemon can use. Therefore, a custom configuration must be created manually after installation.
