LUAPOWER WINDOWS CI SERVER HOWTO:
----------------------------------------------------------------------

* install Git

* install multigit somewhere in your PATH

* download luapower via mgit in `x:/luapower`
  - this folder will be shared with Linux via vboxfs and with OSX via samba.

* set logged user's password in case it has no password and set sharing
on the luapower folder.

* add `%USERPROFILE%/.ssh/id_rsa and authorized_keys files in from vault.
  - this will make git along with its own version of ssh and scp work
  without a password, which in turn will make `mgit ci` work.

* fixate the computer's IP into the router's DHCP.

* install & configure the Bitvise SSH Server. Create a virtual account and 
set bash.exe as shell with full access.

