foxwq API
=========

Sign Up
-------
- each call requires valid `X-APP-ID` and `X-API-KEY` headers. To obtain those, please contact @curlywalrus on the [openfoxwq Discord server](https://discord.gg/RG2KquNWKE).

Notes
-----
- each call requires [Basic Auth](https://datatracker.ietf.org/doc/html/rfc7617) with the username and password of an existing foxwq account. However, the MD5 hash of the password should be used instead of the actual password, in the usual hex string format.
- the first call with a given account might return 500 a couple of times until a proxy connection is established. Please retry those.