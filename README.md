# fix-infinality

This role implements the steps of the [fix-infinality](https://gist.github.com/cryzed/e002e7057435f02cc7894b9e748c5671) of [cryzed](https://gist.github.com/cryzed).

The same [disclaimer](https://gist.github.com/cryzed/e002e7057435f02cc7894b9e748c5671#file-fix-infinality-md) applies to this role as well.

For now this role takes the local.conf contents from the gist.

The role installs the dependencies from the Arch repositories and the aur, creates the links and creates the `/etc/fonts/local.conf` file.

## dependencies

This role depends my a small [aur](https://github.com/knowhy/ansible-role-aur) helper role.
