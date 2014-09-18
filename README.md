## selenium [![Build Status](https://travis-ci.org/ThePixelDeveloper/ansible-selenium.svg?branch=master)](https://travis-ci.org/ThePixelDeveloper/ansible-selenium)

Set up selenium in Debian-like systems.

#### Requirements

* `curl`
* `php` (5.3.2+)

#### Variables

* `selenium_install_dir` [default: `/usr/local/bin`]: Install directory

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
  - selenium
```

#### License

MIT

#### Author Information

Mathew Davies

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/ThePixelDeveloper/ansible-selenium/issues)!
