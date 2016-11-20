# httpforcecache

[![Build Status](https://travis-ci.org/if1live/httpforcecache.svg?branch=master)](https://travis-ci.org/if1live/httpforcecache)

A Transport for Go's http.Client that will cache responses.
If request is success, cache it. else, do not caching.
Based on [httpcache](https://github.com/gregjones/httpcache/).

## Cache backends
see [heepcache Cache backends](https://github.com/gregjones/httpcache/blob/master/README.md)
