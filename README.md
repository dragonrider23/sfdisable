sfdisable
---------

sfdisable is a simple wrapper that disables the sendfile functionality for an application.
This program has only been tested with a Go application but should work for any application that tries to call the system sendfile function.

Installation: `go get -u github.com/dragonrider23/sfdisable`

Usage: `sudo sfdisable [command] [args]`

sfdisable must be ran with root privileges because it makes syscalls that alter how the process is ran. DO NOT USE THIS IN PRODUCTION. This is designed strictly for development use only.
