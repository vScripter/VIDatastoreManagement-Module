## VIDatastoreManagement PowerShell Module

### About

This module contains functions that have been gathered from the community, which aim to bring deeper automation and managability support to datastores and LUNs in a VMware vSphere environment

### Contributions/Credit

A little bit about where the functions came from and how has contributed

__William Lam__ - Functions for managing datastores/SCSI LUNs on VMHosts. Originally by William Lam, at http://blogs.vmware.com/vsphere/2012/01/automating-datastore-storage-device-detachment-in-vsphere-5.html (linking to https://communities.vmware.com/docs/DOC-18008).

__Matt Boren__ - added things like Confirmation and ShouldProcess (-WhatIf) support, ability to act on datastores at a per-host level, not just at "all attached hosts" level, and updated nouns to correspond with the thing on which the function is acting (SCSI LUN on some, instead of datastore) [https://communities.vmware.com/message/2408628#2408628]

__Luc Dekens__ - http://www.lucd.info/2012/04/15/test-if-the-datastore-can-be-unmounted/

__Kevin Kirkpatrick__ - compiled community functions and bundled into module. Renamed some of the functions so that they began with approved verbs. Individual contributions noted via comment based help and/or in-line code comments, within each function. [https://github.com/vScripter | Twitter: @vScripter]
