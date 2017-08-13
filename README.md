# RPM Create Apache VHOST Script

### Script is designed to work RPM based operating systems.

Bash script that makes adding new virtual hosts to Apache web server easy.
Script can me moved to any directory, it doesn't use any relative dependencies and configuration files, but you still can configure script by declaring specific environment variables like:

---
`${APACHE_SERVER_ROOT}`

Location of server's root, directory that contain server's configuration files.

Default value:
`'/etc/httpd'`

---
`${APACHE_DOCUMENT_ROOT}`

Location on disk where document roots for new virtual hosts will be created.

Default value:
`'/var/www'`

---
`${APACHE_SUB_DOMAIN}`

Name of the domain that will be inserted between name of the host and root level domain.

Default value:
`''`

---

### Dependencies:
* bash
* httpd

## Author
* Author: Kevin Rudissaar
* Email: kevin.rudissaar[at]gmail.com
* Twitter: [@KevinRudissaar](https://twitter.com/KevinRudissaar)

## Donate
If you found this script really useful or if you would just like to donate to developer, you can use following donation methods:

[![Donate via PayPal](https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=EGU5RTCF69G82)

BTC: 1HZNkcukFHYF5FKPTvsTnNQNiGQTHZcbR7
