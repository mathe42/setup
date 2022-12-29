Man in the middle attack over http
```
HSTS Strict-Transport-Security: max-age=<expire-time>; includeSubdomains
```

Don't leak URL info
```
Referrer-Policy: no-referrer
```

All Content-Types are correctly set => nosniff needed! (spectre, meltdown) [CORB]
```
X-Content-Type-Options: nosniff
```

Cross Origin Site isolation (spectre, meltdown) [COOP]
```
Cross-Origin-Opener-Policy: same-origin
```

Only embed same origin or other server has to allow it with cors (or crossorigin attribute on image etc) [COEP]
```
Cross-Origin-Embedder-Policy: require-corp
```

Only embed this resoource in this origin not in other origins! [CORP]
```
Cross-Origin-Resource-Policy: same-origin
```

Clickjacking per frame verhindern
```
X-Frame-Options: deny | sameorigin
```

Set SameSite lax for session cookie (prevents CSRF)
In php:
```php
session_set_cookie_params([
  // only https
  'secure' => true,
  // only via header
  'httponly' => true,
  // not cross site
  'samesite' => 'lax'
])
```

