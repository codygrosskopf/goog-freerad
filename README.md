# goog-freerad
Google/Freeradius Configuration

## Overview

This page will describe how to authenticate radius users to Google Secure LDAP using Freeradius. The downside is that mschap will supposedly never work which means pretty much any client straight out of the box won't work. 

### Google Secure LDAP

In this section we will:

- Set up the secure ldap user
- generate certificates
- grant permissions

### Freeradius installation

Debian/Ubuntu:
```sudo apt-get install freeradius freeradius-ldap```

