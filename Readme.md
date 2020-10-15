# Execute

## On Linux

packer build -var-file=vars.json server.json

## On Windows

packer build -var-file vars.json server.json

### Requirements

Packer
VMware Environment
7-8 minutes

### What else

Rename vars_TEMPLATE to to just vars(.json) and fill it out as you see fit.

Also, update passwords in autounattend.xml - search for PASSWORD_HERE and your serial (SERIAL_HERE)
