# sysop: system operations
a NixOS operations frontend for lazy people

### installation:
1. prerequesites

the only prerequesites are `nom` and `nix-search-cli`. please ensure you have them installed before using `sysop`!

2. initial setup

create `~/.local/bin`

`$ mkdir .local/bin`

and allow NixOS to see it by adding `environment.localBinInPath = true;` to your `/etc/nixos/configuration.nix` file.

3. rebuild and reboot!

now you can give it a shot by running `sysop -h`

### options:


| flag |        function        |
|------|------------------------|
|-r    | rebuild                |
|-u    | upgrade                |
|-d    | garbage collection     |
|-p    | nix-shell installation |
|-h    | help                   |
|-s    | search                 |
