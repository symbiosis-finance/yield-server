# Vulnerability Report

**Scan date:** 2026-05-21  
**Ecosystem:** npm  

## Summary

| Metric | Count |
|--------|-------|
| Pre-patch vulnerable (package, version) instances | 87 |
| Post-patch vulnerable instances | 18 |
| **Resolved** | **69** |

## Manifest Changes

```
@babel/runtime: ^7.18.6 → ^7.26.10 (MODERATE)
electron: ^17.1.2 → 39.8.5 (HIGH)
lodash: ^4.17.21 → ^4.18.0 (HIGH)
pg-promise: ^10.11.1 → 11.5.5 (MODERATE)
webpack: ^5.70.0 → ^5.104.1 (CRITICAL)
```

## Remaining Vulnerabilities

| Package | Version | Severity | Advisory IDs |
|---------|---------|----------|-------------|
| @openzeppelin/contracts | 3.4.2-solc-0.7 | CRITICAL | GHSA-7grf-83vw-6f5x, GHSA-88g8-f5mf-f5rj, GHSA-9c22-pwxw-p6hx |
| axios | 0.21.4 | HIGH | GHSA-3p68-rc4w-qgx5, GHSA-43fc-jf86-j433, GHSA-5c9x-8gcm-mpgx |
| @openzeppelin/contracts | 3.4.1-solc-0.7-2 | CRITICAL | GHSA-7grf-83vw-6f5x, GHSA-88g8-f5mf-f5rj, GHSA-9c22-pwxw-p6hx |
| aws-sdk | 2.1693.0 | LOW | GHSA-j965-2qgj-vjmq |
| axios | 0.27.2 | HIGH | GHSA-3p68-rc4w-qgx5, GHSA-43fc-jf86-j433, GHSA-5c9x-8gcm-mpgx |
| elliptic | 6.6.1 | LOW | GHSA-848j-6mx2-7j84 |
| ws | 3.3.3 | HIGH | GHSA-3h5v-q93c-6h6q |
| bn.js | 4.11.6 | MODERATE | GHSA-378v-28hj-76wf |
| fast-xml-parser | 5.2.5 | UNKNOWN | GHSA-37qj-frw5-hhjh, GHSA-8gc5-j5rx-235r, GHSA-fj3w-jwp8-x2g3 |
| file-type | 16.5.4 | MODERATE | GHSA-5v7r-6r5c-r473 |
| request | 2.88.2 | MODERATE | GHSA-p8p7-x288-28g6 |
| form-data | 2.3.3 | CRITICAL | GHSA-fjxv-7rqg-78g4 |
| qs | 6.5.5 | MODERATE | GHSA-6rw7-vpxm-498p |
| tar | 4.4.19 | HIGH | GHSA-34x7-hfp2-rc4v, GHSA-83g3-92jg-28cx, GHSA-8qq5-rm4j-mr97 |
| tar | 6.2.1 | HIGH | GHSA-34x7-hfp2-rc4v, GHSA-83g3-92jg-28cx, GHSA-8qq5-rm4j-mr97 |
| tough-cookie | 2.5.0 | MODERATE | GHSA-72xf-g2v4-qvf3 |
| web3-core-subscriptions | 1.10.4 | LOW | GHSA-hhf6-3xpg-pggx |
| ws | 8.18.0 | UNKNOWN | GHSA-58qx-3vcg-4xpx |

## Escalations

### @babel/helpers@7.19.0 (MODERATE)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.@babel/helpers = "7.26.10"`

### @babel/runtime-corejs3@7.19.0 (MODERATE)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.@babel/runtime-corejs3 = "7.26.10"`

### @babel/traverse@7.19.0 (CRITICAL)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.@babel/traverse = "7.23.2"`

### @openzeppelin/contracts@3.4.2-solc-0.7 (CRITICAL)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.@openzeppelin/contracts = "?"`

### js-yaml@4.1.0 (MODERATE)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.js-yaml = "4.1.1"`

### semver@7.3.7 (HIGH)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.semver = "7.5.2"`

### axios@0.21.4 (HIGH)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.axios = "0.31.1"`

### ws@7.5.9 (HIGH)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.ws = "7.5.10"`

### ajv@6.12.6 (MODERATE)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.ajv = "8.18.0"`

### bn.js@4.12.0 (MODERATE)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.bn.js = "5.2.3"`

### aws-sdk@2.1210.0 (LOW)
- **Path:** direct
- **Why no fix:** No fixed version published for this advisory
- **Override recipe:** `N/A`

### base-x@3.0.9 (HIGH)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.base-x = "3.0.11"`

### body-parser@1.20.0 (HIGH)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.body-parser = "1.20.3"`

### qs@6.10.3 (HIGH)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.qs = "6.14.2"`

### brace-expansion@1.1.11 (MODERATE)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.brace-expansion = "2.0.3"`

### braces@3.0.2 (HIGH)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.braces = "3.0.3"`

### browserify-sign@4.2.1 (HIGH)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.browserify-sign = "4.2.2"`

### cross-spawn@6.0.5 (HIGH)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.cross-spawn = "7.0.5"`

### cipher-base@1.0.4 (CRITICAL)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.cipher-base = "1.0.5"`

### cookie@0.4.2 (LOW)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.cookie = "0.7.0"`

### cookiejar@2.1.3 (MODERATE)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.cookiejar = "2.1.4"`

### decode-uri-component@0.2.0 (HIGH)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.decode-uri-component = "0.2.1"`

### diff@5.0.0 (LOW)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.diff = "5.2.2"`

### elliptic@6.5.4 (CRITICAL)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.elliptic = "6.6.1"`

### es5-ext@0.10.62 (LOW)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.es5-ext = "0.10.63"`

### express@4.18.1 (MODERATE)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.express = "4.20.0"`

### file-type@16.5.4 (MODERATE)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.file-type = "21.3.1"`

### flatted@3.2.7 (HIGH)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.flatted = "3.4.2"`

### follow-redirects@1.15.1 (MODERATE)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.follow-redirects = "1.16.0"`

### form-data@4.0.0 (CRITICAL)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.form-data = "4.0.4"`

### got@9.6.0 (MODERATE)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.got = "11.8.5"`

### http-cache-semantics@4.1.0 (HIGH)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.http-cache-semantics = "4.1.1"`

### immutable@4.1.0 (HIGH)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.immutable = "4.3.8"`

### json5@2.2.1 (HIGH)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.json5 = "2.2.2"`

### loader-utils@2.0.2 (CRITICAL)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.loader-utils = "2.0.4"`

### micromatch@4.0.5 (MODERATE)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.micromatch = "4.0.8"`

### min-document@2.19.0 (LOW)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.min-document = "2.19.1"`

### minimatch@3.1.2 (HIGH)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.minimatch = "5.1.8"`

### nanoid@3.3.3 (MODERATE)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.nanoid = "3.3.8"`

### path-to-regexp@0.1.7 (HIGH)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.path-to-regexp = "0.1.13"`

### pbkdf2@3.1.2 (CRITICAL)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.pbkdf2 = "3.1.3"`

### picomatch@2.3.1 (HIGH)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.picomatch = "2.3.2"`

### request@2.88.2 (MODERATE)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.request = "?"`

### secp256k1@4.0.3 (HIGH)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.secp256k1 = "4.0.4"`

### send@0.18.0 (LOW)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.send = "0.19.0"`

### serialize-javascript@6.0.0 (HIGH)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.serialize-javascript = "7.0.5"`

### serve-static@1.15.0 (LOW)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.serve-static = "1.16.0"`

### sha.js@2.4.11 (CRITICAL)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.sha.js = "2.4.12"`

### simple-git@3.14.0 (CRITICAL)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.simple-git = "3.36.0"`

### tar@4.4.19 (HIGH)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.tar = "7.5.11"`

### tmp@0.0.33 (LOW)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.tmp = "0.2.4"`

### tough-cookie@2.5.0 (MODERATE)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.tough-cookie = "4.1.3"`

### undici@5.10.0 (HIGH)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.undici = "6.24.0"`

### web3-core-method@1.7.5 (LOW)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.web3-core-method = "?"`

### web3-core-subscriptions@1.7.5 (LOW)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.web3-core-subscriptions = "?"`

### word-wrap@1.2.3 (MODERATE)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.word-wrap = "1.2.4"`

### xml2js@0.4.19 (MODERATE)
- **Path:** unknown
- **Why no fix:** Could not trace to a direct manifest ancestor
- **Override recipe:** `overrides.xml2js = "0.5.0"`

