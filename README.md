Yourls-Memcached
================

Memcached plugin for YOURLS

!! Be careful, don't use in production environment (or at your own risk). Unstable for the moment. !!

This plugin is based on "Yourls-APC-Cache" by Ian Barber (https://github.com/ianbarber)


Install
================
Copy memcached in the plugin directory (user/plugins/) and activate it in the admin.


Requirements
================
One Memcached server (running) and Memcached PHP extension (http://pecl.php.net/package/memcached)


Default configuration
================
Memcached IP: 127.0.0.1 (localhost)
Memcached port: 11211

For custom configuration, add in your config.php
```
define("MEMCACHED_IP", 127.0.0.1);
define("MEMCACHED_PORT", 11211);
```

TODO
================
Check all functions is working (especially statistics)
Optimize code
Support multiple memcached servers