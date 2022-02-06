
# Cache component

The cache component allows you to view and manage your server's cache. Magic's server
cache is typically used to make sure that expensive operations are cached, preventing your
server from becoming exhausted due to having to execute expensive operations often, when the
result of the expensive operation typically doesn't change for some time after initially
executed. There are a whole range of slots in Magic related to caching, and you can
[read more about the internals of your cache here](/documentation/magic.lambda.caching/).

The cache component allows you to peek into your server's cache, and/or administrate
your items, individually, in addition to purging/emptying your server's cache.

* [Back to middleware documentation](/documentation/magic/)
* [Back to main documentation](/documentation/)