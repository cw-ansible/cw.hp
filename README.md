<!--

---
lang: american
---
-->

[![Build Status](https://travis-ci.org/cw-ansible/cw.dell.svg?branch=master)](https://travis-ci.org/cw-ansible/cw.hp)
[![Tweet this](http://img.shields.io/badge/Tweet-it00aced.svg)](https://twitter.com/intent/tweet?tw_p=tweetbutton&via=renard_0&text=Install%20%23Dell%20%23OpenManage%20tools%20with%20%23Ansible)
[![Follow me on twitter](http://img.shields.io/badge/Twitter-Follow-00aced.svg)](https://twitter.com/intent/follow?region=follow_link&screen_name=renard_0&tw_p=followbutton)

# Install HP utils with ansible

This Ansible role install
[HP Software Delivery Repository](http://downloads.linux.hpe.com/SDR/repo/)
tools.

## Usage

This module is pretty straightforward, you only need to include `cw.hp` in
your playbook for basic installation.

[files/etc/init.d/ilo-set]() is installed to configure *iLO* interface. you
can run `/etc/init.d/ilo-set start` to configure *iLO*. Please note that
this version actualy runs for `iLO` 3 and 4. It might work with version 2
but not with iLO 100. You may also want to upgrade your iLO firmware. 

## Configuration

See specific documentation in `defaults/main.yml`


## Links

- [HP Software Delivery Repository](http://downloads.linux.hpe.com/SDR/repo/)


## Copyright

Author: Sébastien Gross `<seb•ɑƬ•chezwam•ɖɵʈ•org>` [@renard_0](https://twitter.com/renard_0)

License: WTFPL, grab your copy here: http://www.wtfpl.net

