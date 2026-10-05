<!-- tyhp-readme:start -->
# tyhpdef/guzzlehttp-promises

Tyhp type definitions for `guzzlehttp/promises` `3.0.2`.

```bash
composer require --dev tyhpdef/guzzlehttp-promises:3.0.2
```

This is a metapackage. Composer also installs `tyhpdef/guzzlehttp-promises-impl` (type files).
Require **this** name, not `tyhpdef/guzzlehttp-promises-impl`.

See https://tyhplang.com.

## Maintain `guzzlehttp/promises`? Ship the types yourself

If you are a Packagist maintainer of `guzzlehttp/promises`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/guzzlehttp-promises-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `guzzlehttp/promises` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/guzzlehttp-promises": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `guzzlehttp/promises` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `guzzlehttp/promises` with a real constraint,
   `"replace": { "tyhpdef/guzzlehttp-promises": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `guzzlehttp/promises` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/guzzlehttp-promises` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
