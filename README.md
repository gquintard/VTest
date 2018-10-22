# VTest 

# The HTTP test-program formerly known as Varnishtest

This project is the (almost) unvarnished varnishtest program, made
available as a stand-alone program because it can be used to test
all sorts of HTTP clients, servers and proxies.

If you want to join the fun, email me.

Poul-Henning

# HISTORY

The initial source tree is generated by running the `convert.sh`
script over a Varnish-Cache trunk tree rev 7161dcf9d9f5380ffd.

# TODO:

* Detect content of config.h as required

* Compile vtc_varnish.c and vtc_logexpect.c only if we can find
  a libvarnishapi installed on the system. (done for meson)

# NOT-TODO:

* Autocrappery

*EOF*
