# Consul Chocolatey Package

## Up and running

Run download.bat to get the binaries

Build the package using `cpack`

## TODO

Create powershell scripts that downloads, builds, and pushes the package

## Package Parameters
The package parameters can be set - https://www.consul.io/docs/agent/options.html
These parameters can be passed to the installer with the use of `-params`.
To escape quotes in params please use ""\"
Example: -params '-config-file=""\"%PROGRAMDATA%\consul\dsc config\default.json\""" -config-dir=%PROGRAMDATA%\consul\config1 -config-dir=""\"%PROGRAMDATA%\consul\extra config\"""'.
