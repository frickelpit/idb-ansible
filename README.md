# ansible playbook for installing the IDB

## General

This ansible playbook can be used to install the IDB from the bytemine
IDB repo.

## Configuration

Each role has its own defaults/main.yml where you can configure several values, e.g. the names of the cert and key to access the bytemine IDB repo and the hostname.

## Issues
The ldap task is not yet usable, so you have to configure ldap manually.