eza-pkgsrc
==========

NetBSD [pkgsrc][4] script for `eza`.

You can find `eza` [here][1]

Installation
------------

Copy `sysutils/eza` folder to `/usr/pkgsrc` directory.

NOTE: If your pkgsrc directory is different from above, copy to the respective
place.

Usage
-----

Once you have copied the folder, install it as you would do for any port.

`$ cd /usr/pkgsrc/sysutils/eza`<br>
`$ make install clean`

For a list of dependencies for the build check [here][2]

NOTE: If you are using pkgsrc in a non NetBSD system, replace `make` with
`bmake` in the above ezample.

Credits
-------

* `eza` is developed and maintained by the [Benjamin Sago][3]
* Thanks to `pin@` and `wiz@` for reviewing and helping migrate 
  exa to eza package.

License
-------

BSD 2-clause. See LICENSE.

[1]: https://eza.rocks/
[2]: https://github.com/eza-community/eza/blob/main/INSTALL.md
[3]: https://github.com/cafkafk
[4]: http://pkgsrc.se/sysutils/eza
