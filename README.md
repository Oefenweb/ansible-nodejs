## nodejs
 
[![Build Status](https://travis-ci.org/Oefenweb/ansible-nodejs.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-nodejs) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-nodejs-blue.svg)](https://galaxy.ansible.com/list#/roles/1814)

Set up the latest version of nodejs and npm in Ubuntu systems.

#### Requirements

* `python-apt`

#### Variables

* `nodejs_install` [default: `[build-essential]`]: Packages to install
* `nodejs_npm_packages` [default: `[]`]: Node.js packages to install (globally)

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
  - nodejs
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-nodejs/issues)!
