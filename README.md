IE8 Cache Buster
===================

Setup to investigate IE8's caching behavior. You can use CloudFlare for a realistic setup.

Before: we have to add a cachebuster to prevent IE8 from aggressively caching Ajax requests.

Conclusion: To prevent IE8 agressive caching we need to use both max-age (Cache-Control) and *Expires* in our caching headers.

tldr: use proper caching headers and IE8 will play nice.
