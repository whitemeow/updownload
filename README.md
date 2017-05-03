# updownload
upload and download with OSS

![hierarchy](http://oi7vwcaww.bkt.clouddn.com/updownload.jpg)

For upload and download, each can access cache and OSS.
For all-in-all deploy, download and upload don't need to share the same content in cache, they can use private cache, such as Map in memory.
For cluster deploy, download services need to share cached data, so we can use public cache such as memcached.
