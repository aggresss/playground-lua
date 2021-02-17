# openresty playground
openresty -p `pwd` -c conf/hello.conf
openresty -p `pwd` -c conf/hello.conf -s quit
openresty -p `pwd` -c conf/hello.conf -s reload

# Reference

- https://github.com/chronolaw/openresty_dev

