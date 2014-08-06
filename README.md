This is a simple Makefile to manage a certificate authority.

You can enroll server certificates, client certificates and 
even smartcard certificates using the pkcs11-tool.

It could also publish your CRL at some CDP and
publish the user certificate in an LDAP directory

Getting started
===============

You need to create a file openssl.cnf in the local directory
that can contain all your extensions.

Take the openssl.cnf.example as stating point. 
Change all example.com occurences.

Modify the settings in the Makefile itself.

Run

   make

to get a help.

Then run

   make initca

to create the CA key and CA certificate.
