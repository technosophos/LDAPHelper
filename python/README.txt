ldaphelper
==========

This package contains a small LDAP helping library designed to 
be used in conjunction with python-ldap.

This library was developed as an example for a series of articles
published by Packt Publishing.

The library is licensed under an MIT style license or under the GPL v2 license 
(the choice is yours). See MIT.txt or GPL.txt for the text of each license.

Installation:
=============
Put the ldaphelper.py file in your Python path.

Usage:
======
From a Python script or shell, 'import ldaphelper' and use it!

The main tool provided in ldaphelper is the LDAPSearchResult class. This is
a wrapper around data returned from an LDAP server. Typically, a set of results
are turned into LDAPSearchResults using the following function:

resultList = ldaphelper.get_search_results(results)

The results object above is the object returned from an LDAP search. The
resultList array is a list of LDAPSearchResult objects.

Documentation:
==============

For documentation, see:
http://aleph-null.tv/article/20071218-1403-65.xml/LDAP-Development-in-Python%2C-Part-2
OR
http://www.packtpub.com/article/python-ldap-applications-ldap-opearations

This program comes with no warranty whatsoever.

2008, Matt Butcher matt @@ aleph-null.tv
