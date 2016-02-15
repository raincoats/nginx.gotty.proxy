# nginx gotty proxy

After trying for ages to proxy [gotty](https://github.com/yudai/gotty) behind nginx, and I think I discovered how to do it. This seems to work for me.

By default, enabling this will make http://example.com/tty/ go to gotty. You can change it in the rewrite lines. It also expects a gotty server listening on localhost and running on port 2600.
