# drupal-lando-kickstart

Purpose of this repo is to provide kick-start for new project.

It uses [Acquia recipe](https://docs.lando.dev/config/acquia.html) for Lando as base and adds following

* Ability to tail Drupal logs
  (for this please use syslog module in your site)
* Ability to enable disable XDEBUG
* XHPROF (requires Drupal's [XHPROF module](https://www.drupal.org/project/xhprof))
* PHP MyAdmin.
