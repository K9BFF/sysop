# sysop: system operations
a nixos operations frontent for lazy people

### installation:
1. prerequesites\n
the only prerequesite is `nom`. please ensure you have it installed before using `sysop`!

2. initial setup
create `~/.local/bin`
`$ mkdir .local/bin`

and allow NixOS to see it by adding
`environment.localBinInPath = true;` to your `/etc/nixos/configuration.nix` file.

3. reboot!

now you can give it a shot by running `sysop -h`

### options:


| flag |        function        |
|------|------------------------|
|-r    | rebuild                |
|-u    | upgrade                |
|-d    | garbage collection     |
|-p    | nix-shell installation |
|-h    | help                   |
