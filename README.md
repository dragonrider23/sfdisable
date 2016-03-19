sfdisable
---------

sfdisable is a simple wrapper that disables the sendfile functionality for a Golang application.

Installation: `go get -u github.com/dragonrider23/sfdisable`

Usage: `sudo sfdisable some-command -f args`

sfdisable must be ran with root privileges because it makes syscalls that alter how the process is ran. DO NOT USE THIS IN PRODUCTION. This is designed strictly for development use only.
