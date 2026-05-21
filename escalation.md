# Escalation Report — Vulnerabilities Without Clean Fix Paths

**Date:** 2026-05-21

The following packages cannot be patched by bumping a manifest entry alone.
Overrides would mechanically resolve them but were NOT applied automatically.
Review each item and decide whether to apply the suggested override.

---

## Item 1 — @babel/helpers (MODERATE)

| Field | Value |
|-------|-------|
| Package | `@babel/helpers@7.19.0` |
| Severity | MODERATE |
| Advisory IDs | GHSA-968p-4wvh-cqc8 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.@babel/helpers = "7.26.10"` |

- **GHSA-968p-4wvh-cqc8**: Babel has inefficient RegExp complexity in generated code with .replace when transpiling named captu

## Item 2 — @babel/runtime-corejs3 (MODERATE)

| Field | Value |
|-------|-------|
| Package | `@babel/runtime-corejs3@7.19.0` |
| Severity | MODERATE |
| Advisory IDs | GHSA-968p-4wvh-cqc8 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.@babel/runtime-corejs3 = "7.26.10"` |

- **GHSA-968p-4wvh-cqc8**: Babel has inefficient RegExp complexity in generated code with .replace when transpiling named captu

## Item 3 — @babel/traverse (CRITICAL)

| Field | Value |
|-------|-------|
| Package | `@babel/traverse@7.19.0` |
| Severity | CRITICAL |
| Advisory IDs | GHSA-67hx-6x53-jw92 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.@babel/traverse = "7.23.2"` |

- **GHSA-67hx-6x53-jw92**: Babel vulnerable to arbitrary code execution when compiling specifically crafted malicious code

## Item 4 — @openzeppelin/contracts (CRITICAL)

| Field | Value |
|-------|-------|
| Package | `@openzeppelin/contracts@3.4.2-solc-0.7` |
| Severity | CRITICAL |
| Advisory IDs | GHSA-fg47-3c2x-m2wr, GHSA-mx2q-35m2-x2rh, GHSA-7grf-83vw-6f5x, GHSA-88g8-f5mf-f5rj, GHSA-9c22-pwxw-p6hx |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.@openzeppelin/contracts = "?"` |

- **GHSA-fg47-3c2x-m2wr**: TimelockController vulnerability in OpenZeppelin Contracts 
- **GHSA-mx2q-35m2-x2rh**: OpenZeppelin Contracts TransparentUpgradeableProxy clashing selector calls may not be delegated
- **GHSA-7grf-83vw-6f5x**: OpenZeppelin Contracts ERC165Checker unbounded gas consumption

## Item 5 — js-yaml (MODERATE)

| Field | Value |
|-------|-------|
| Package | `js-yaml@4.1.0` |
| Severity | MODERATE |
| Advisory IDs | GHSA-mh29-5h37-fv8m |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.js-yaml = "4.1.1"` |

- **GHSA-mh29-5h37-fv8m**: js-yaml has prototype pollution in merge (<<)

## Item 6 — semver (HIGH)

| Field | Value |
|-------|-------|
| Package | `semver@7.3.7` |
| Severity | HIGH |
| Advisory IDs | GHSA-c2qf-rxjj-qqgw |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.semver = "7.5.2"` |

- **GHSA-c2qf-rxjj-qqgw**: semver vulnerable to Regular Expression Denial of Service

## Item 7 — axios (HIGH)

| Field | Value |
|-------|-------|
| Package | `axios@0.21.4` |
| Severity | HIGH |
| Advisory IDs | GHSA-vf2m-468p-8v99, GHSA-fvcv-3m26-pcqx, GHSA-m7pr-hjqh-92cm, GHSA-43fc-jf86-j433, GHSA-62hf-57xw-28j9 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.axios = "0.31.1"` |

- **GHSA-vf2m-468p-8v99**: Axios: HTTP adapter streamed responses bypass maxContentLength
- **GHSA-fvcv-3m26-pcqx**: Axios has Unrestricted Cloud Metadata Exfiltration via Header Injection Chain
- **GHSA-m7pr-hjqh-92cm**: Axios: no_proxy bypass via IP alias allows SSRF

## Item 8 — ws (HIGH)

| Field | Value |
|-------|-------|
| Package | `ws@7.5.9` |
| Severity | HIGH |
| Advisory IDs | GHSA-3h5v-q93c-6h6q |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.ws = "7.5.10"` |

- **GHSA-3h5v-q93c-6h6q**: ws affected by a DoS when handling a request with many HTTP headers

## Item 9 — ajv (MODERATE)

| Field | Value |
|-------|-------|
| Package | `ajv@6.12.6` |
| Severity | MODERATE |
| Advisory IDs | GHSA-2g4f-4pwh-qvx6 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.ajv = "8.18.0"` |

- **GHSA-2g4f-4pwh-qvx6**: ajv has ReDoS when using `$data` option

## Item 10 — bn.js (MODERATE)

| Field | Value |
|-------|-------|
| Package | `bn.js@4.12.0` |
| Severity | MODERATE |
| Advisory IDs | GHSA-378v-28hj-76wf |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.bn.js = "5.2.3"` |

- **GHSA-378v-28hj-76wf**: bn.js affected by an infinite loop

## Item 11 — aws-sdk (LOW)

| Field | Value |
|-------|-------|
| Package | `aws-sdk@2.1210.0` |
| Severity | LOW |
| Advisory IDs | GHSA-j965-2qgj-vjmq |
| Dep path | direct |
| Why no clean fix | No fixed version published for this advisory |
| Override recipe | `N/A` |

- **GHSA-j965-2qgj-vjmq**: JavaScript SDK v2 users should add validation to the region parameter value in or migrate to v3

## Item 12 — base-x (HIGH)

| Field | Value |
|-------|-------|
| Package | `base-x@3.0.9` |
| Severity | HIGH |
| Advisory IDs | GHSA-xq7p-g2vc-g82p |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.base-x = "3.0.11"` |

- **GHSA-xq7p-g2vc-g82p**: Homograph attack allows Unicode lookalike characters to bypass validation.

## Item 13 — body-parser (HIGH)

| Field | Value |
|-------|-------|
| Package | `body-parser@1.20.0` |
| Severity | HIGH |
| Advisory IDs | GHSA-qwcr-r2fm-qrc7 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.body-parser = "1.20.3"` |

- **GHSA-qwcr-r2fm-qrc7**: body-parser vulnerable to denial of service when url encoding is enabled

## Item 14 — qs (HIGH)

| Field | Value |
|-------|-------|
| Package | `qs@6.10.3` |
| Severity | HIGH |
| Advisory IDs | GHSA-hrpp-h998-j3pp, GHSA-6rw7-vpxm-498p, GHSA-w7fw-mjwx-w883 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.qs = "6.14.2"` |

- **GHSA-hrpp-h998-j3pp**: qs vulnerable to Prototype Pollution
- **GHSA-6rw7-vpxm-498p**: qs's arrayLimit bypass in its bracket notation allows DoS via memory exhaustion
- **GHSA-w7fw-mjwx-w883**: qs's arrayLimit bypass in comma parsing allows denial of service

## Item 15 — brace-expansion (MODERATE)

| Field | Value |
|-------|-------|
| Package | `brace-expansion@1.1.11` |
| Severity | MODERATE |
| Advisory IDs | GHSA-f886-m6hf-6m8v, GHSA-v6h2-p8h4-qcjw |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.brace-expansion = "2.0.3"` |

- **GHSA-f886-m6hf-6m8v**: brace-expansion: Zero-step sequence causes process hang and memory exhaustion
- **GHSA-v6h2-p8h4-qcjw**: brace-expansion Regular Expression Denial of Service vulnerability

## Item 16 — braces (HIGH)

| Field | Value |
|-------|-------|
| Package | `braces@3.0.2` |
| Severity | HIGH |
| Advisory IDs | GHSA-grv7-fg5c-xmjg |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.braces = "3.0.3"` |

- **GHSA-grv7-fg5c-xmjg**: Uncontrolled resource consumption in braces

## Item 17 — browserify-sign (HIGH)

| Field | Value |
|-------|-------|
| Package | `browserify-sign@4.2.1` |
| Severity | HIGH |
| Advisory IDs | GHSA-x9w5-v3q2-3rhw |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.browserify-sign = "4.2.2"` |

- **GHSA-x9w5-v3q2-3rhw**: browserify-sign upper bound check issue in `dsaVerify` leads to a signature forgery attack

## Item 18 — cross-spawn (HIGH)

| Field | Value |
|-------|-------|
| Package | `cross-spawn@6.0.5` |
| Severity | HIGH |
| Advisory IDs | GHSA-3xgq-45jj-v275 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.cross-spawn = "7.0.5"` |

- **GHSA-3xgq-45jj-v275**: Regular Expression Denial of Service (ReDoS) in cross-spawn

## Item 19 — cipher-base (CRITICAL)

| Field | Value |
|-------|-------|
| Package | `cipher-base@1.0.4` |
| Severity | CRITICAL |
| Advisory IDs | GHSA-cpq7-6gpm-g9rc |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.cipher-base = "1.0.5"` |

- **GHSA-cpq7-6gpm-g9rc**: cipher-base is missing type checks, leading to hash rewind and passing on crafted data

## Item 20 — cookie (LOW)

| Field | Value |
|-------|-------|
| Package | `cookie@0.4.2` |
| Severity | LOW |
| Advisory IDs | GHSA-pxg6-pf52-xh8x |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.cookie = "0.7.0"` |

- **GHSA-pxg6-pf52-xh8x**: cookie accepts cookie name, path, and domain with out of bounds characters

## Item 21 — cookiejar (MODERATE)

| Field | Value |
|-------|-------|
| Package | `cookiejar@2.1.3` |
| Severity | MODERATE |
| Advisory IDs | GHSA-h452-7996-h45h |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.cookiejar = "2.1.4"` |

- **GHSA-h452-7996-h45h**: cookiejar Regular Expression Denial of Service via Cookie.parse function

## Item 22 — decode-uri-component (HIGH)

| Field | Value |
|-------|-------|
| Package | `decode-uri-component@0.2.0` |
| Severity | HIGH |
| Advisory IDs | GHSA-w573-4hg7-7wgq |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.decode-uri-component = "0.2.1"` |

- **GHSA-w573-4hg7-7wgq**: decode-uri-component vulnerable to Denial of Service (DoS)

## Item 23 — diff (LOW)

| Field | Value |
|-------|-------|
| Package | `diff@5.0.0` |
| Severity | LOW |
| Advisory IDs | GHSA-73rr-hh4g-fpgx |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.diff = "5.2.2"` |

- **GHSA-73rr-hh4g-fpgx**: jsdiff has a Denial of Service vulnerability in parsePatch and applyPatch

## Item 24 — elliptic (CRITICAL)

| Field | Value |
|-------|-------|
| Package | `elliptic@6.5.4` |
| Severity | CRITICAL |
| Advisory IDs | GHSA-49q7-c7j4-3p7m, GHSA-f7q4-pwc6-w24p, GHSA-977x-g7h5-7qgw, GHSA-fc9h-whq2-v747, GHSA-848j-6mx2-7j84 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.elliptic = "6.6.1"` |

- **GHSA-49q7-c7j4-3p7m**: Elliptic allows BER-encoded signatures
- **GHSA-f7q4-pwc6-w24p**: Elliptic's EDDSA missing signature length check
- **GHSA-977x-g7h5-7qgw**: Elliptic's ECDSA missing check for whether leading bit of r and s is zero

## Item 25 — es5-ext (LOW)

| Field | Value |
|-------|-------|
| Package | `es5-ext@0.10.62` |
| Severity | LOW |
| Advisory IDs | GHSA-4gmj-3p3h-gm8h |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.es5-ext = "0.10.63"` |

- **GHSA-4gmj-3p3h-gm8h**: es5-ext vulnerable to Regular Expression Denial of Service in `function#copy` and `function#toString

## Item 26 — express (MODERATE)

| Field | Value |
|-------|-------|
| Package | `express@4.18.1` |
| Severity | MODERATE |
| Advisory IDs | GHSA-rv95-896h-c2vc, GHSA-qw6h-vgh9-j6wx |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.express = "4.20.0"` |

- **GHSA-rv95-896h-c2vc**: Express.js Open Redirect in malformed URLs
- **GHSA-qw6h-vgh9-j6wx**: express vulnerable to XSS via response.redirect()

## Item 27 — file-type (MODERATE)

| Field | Value |
|-------|-------|
| Package | `file-type@16.5.4` |
| Severity | MODERATE |
| Advisory IDs | GHSA-5v7r-6r5c-r473 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.file-type = "21.3.1"` |

- **GHSA-5v7r-6r5c-r473**: file-type affected by infinite loop in ASF parser on malformed input with zero-size sub-header

## Item 28 — flatted (HIGH)

| Field | Value |
|-------|-------|
| Package | `flatted@3.2.7` |
| Severity | HIGH |
| Advisory IDs | GHSA-rf6f-7fwh-wjgh, GHSA-25h7-pfq9-p65f |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.flatted = "3.4.2"` |

- **GHSA-rf6f-7fwh-wjgh**: Prototype Pollution via parse() in NodeJS flatted
- **GHSA-25h7-pfq9-p65f**: flatted vulnerable to unbounded recursion DoS in parse() revive phase

## Item 29 — follow-redirects (MODERATE)

| Field | Value |
|-------|-------|
| Package | `follow-redirects@1.15.1` |
| Severity | MODERATE |
| Advisory IDs | GHSA-r4q5-vmmm-2653, GHSA-jchw-25xp-jwwc, GHSA-cxjh-pqwp-8mfp |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.follow-redirects = "1.16.0"` |

- **GHSA-r4q5-vmmm-2653**: follow-redirects leaks Custom Authentication Headers to Cross-Domain Redirect Targets
- **GHSA-jchw-25xp-jwwc**: Follow Redirects improperly handles URLs in the url.parse() function
- **GHSA-cxjh-pqwp-8mfp**: follow-redirects' Proxy-Authorization header kept across hosts

## Item 30 — form-data (CRITICAL)

| Field | Value |
|-------|-------|
| Package | `form-data@4.0.0` |
| Severity | CRITICAL |
| Advisory IDs | GHSA-fjxv-7rqg-78g4 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.form-data = "4.0.4"` |

- **GHSA-fjxv-7rqg-78g4**: form-data uses unsafe random function in form-data for choosing boundary

## Item 31 — got (MODERATE)

| Field | Value |
|-------|-------|
| Package | `got@9.6.0` |
| Severity | MODERATE |
| Advisory IDs | GHSA-pfrx-2q88-qq97 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.got = "11.8.5"` |

- **GHSA-pfrx-2q88-qq97**: Got allows a redirect to a UNIX socket

## Item 32 — http-cache-semantics (HIGH)

| Field | Value |
|-------|-------|
| Package | `http-cache-semantics@4.1.0` |
| Severity | HIGH |
| Advisory IDs | GHSA-rc47-6667-2j5j |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.http-cache-semantics = "4.1.1"` |

- **GHSA-rc47-6667-2j5j**: http-cache-semantics vulnerable to Regular Expression Denial of Service

## Item 33 — immutable (HIGH)

| Field | Value |
|-------|-------|
| Package | `immutable@4.1.0` |
| Severity | HIGH |
| Advisory IDs | GHSA-wf6x-7x77-mvgw |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.immutable = "4.3.8"` |

- **GHSA-wf6x-7x77-mvgw**: Immutable is vulnerable to Prototype Pollution

## Item 34 — json5 (HIGH)

| Field | Value |
|-------|-------|
| Package | `json5@2.2.1` |
| Severity | HIGH |
| Advisory IDs | GHSA-9c47-m6qq-7p4h |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.json5 = "2.2.2"` |

- **GHSA-9c47-m6qq-7p4h**: Prototype Pollution in JSON5 via Parse Method

## Item 35 — loader-utils (CRITICAL)

| Field | Value |
|-------|-------|
| Package | `loader-utils@2.0.2` |
| Severity | CRITICAL |
| Advisory IDs | GHSA-76p3-8jx3-jpfq, GHSA-3rfm-jhwj-7488, GHSA-hhq3-ff78-jv3g |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.loader-utils = "2.0.4"` |

- **GHSA-76p3-8jx3-jpfq**: Prototype pollution in webpack loader-utils
- **GHSA-3rfm-jhwj-7488**: loader-utils is vulnerable to Regular Expression Denial of Service (ReDoS) via url variable
- **GHSA-hhq3-ff78-jv3g**: loader-utils is vulnerable to Regular Expression Denial of Service (ReDoS)

## Item 36 — micromatch (MODERATE)

| Field | Value |
|-------|-------|
| Package | `micromatch@4.0.5` |
| Severity | MODERATE |
| Advisory IDs | GHSA-952p-6rrq-rcjv |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.micromatch = "4.0.8"` |

- **GHSA-952p-6rrq-rcjv**: Regular Expression Denial of Service (ReDoS) in micromatch

## Item 37 — min-document (LOW)

| Field | Value |
|-------|-------|
| Package | `min-document@2.19.0` |
| Severity | LOW |
| Advisory IDs | GHSA-rx8g-88g5-qh64 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.min-document = "2.19.1"` |

- **GHSA-rx8g-88g5-qh64**: min-document vulnerable to prototype pollution

## Item 38 — minimatch (HIGH)

| Field | Value |
|-------|-------|
| Package | `minimatch@3.1.2` |
| Severity | HIGH |
| Advisory IDs | GHSA-23c5-xmqv-rm74, GHSA-3ppc-4f35-3m26, GHSA-7r86-cg39-jmmj |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.minimatch = "5.1.8"` |

- **GHSA-23c5-xmqv-rm74**: minimatch ReDoS: nested *() extglobs generate catastrophically backtracking regular expressions
- **GHSA-3ppc-4f35-3m26**: minimatch has a ReDoS via repeated wildcards with non-matching literal in pattern
- **GHSA-7r86-cg39-jmmj**: minimatch has ReDoS: matchOne() combinatorial backtracking via multiple non-adjacent GLOBSTAR segmen

## Item 39 — nanoid (MODERATE)

| Field | Value |
|-------|-------|
| Package | `nanoid@3.3.3` |
| Severity | MODERATE |
| Advisory IDs | GHSA-mwcw-c2x4-8c55 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.nanoid = "3.3.8"` |

- **GHSA-mwcw-c2x4-8c55**: Predictable results in nanoid generation when given non-integer values

## Item 40 — path-to-regexp (HIGH)

| Field | Value |
|-------|-------|
| Package | `path-to-regexp@0.1.7` |
| Severity | HIGH |
| Advisory IDs | GHSA-9wv6-86v2-598j, GHSA-37ch-88jc-xwx2, GHSA-rhx6-c78j-4q9w |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.path-to-regexp = "0.1.13"` |

- **GHSA-9wv6-86v2-598j**: path-to-regexp outputs backtracking regular expressions
- **GHSA-37ch-88jc-xwx2**: path-to-regexp vulnerable to Regular Expression Denial of Service via multiple route parameters
- **GHSA-rhx6-c78j-4q9w**: path-to-regexp contains a ReDoS

## Item 41 — pbkdf2 (CRITICAL)

| Field | Value |
|-------|-------|
| Package | `pbkdf2@3.1.2` |
| Severity | CRITICAL |
| Advisory IDs | GHSA-h7cp-r72f-jxh6, GHSA-v62p-rq8g-8h59 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.pbkdf2 = "3.1.3"` |

- **GHSA-h7cp-r72f-jxh6**: pbkdf2 returns predictable uninitialized/zero-filled memory for non-normalized or unimplemented algo
- **GHSA-v62p-rq8g-8h59**: pbkdf2 silently disregards Uint8Array input, returning static keys

## Item 42 — picomatch (HIGH)

| Field | Value |
|-------|-------|
| Package | `picomatch@2.3.1` |
| Severity | HIGH |
| Advisory IDs | GHSA-c2c7-rcm5-vvqj, GHSA-3v7f-55p6-f55p |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.picomatch = "2.3.2"` |

- **GHSA-c2c7-rcm5-vvqj**: Picomatch has a ReDoS vulnerability via extglob quantifiers
- **GHSA-3v7f-55p6-f55p**: Picomatch: Method Injection in POSIX Character Classes causes incorrect Glob Matching

## Item 43 — request (MODERATE)

| Field | Value |
|-------|-------|
| Package | `request@2.88.2` |
| Severity | MODERATE |
| Advisory IDs | GHSA-p8p7-x288-28g6 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.request = "?"` |

- **GHSA-p8p7-x288-28g6**: Server-Side Request Forgery in Request

## Item 44 — secp256k1 (HIGH)

| Field | Value |
|-------|-------|
| Package | `secp256k1@4.0.3` |
| Severity | HIGH |
| Advisory IDs | GHSA-584q-6j8j-r5pm |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.secp256k1 = "4.0.4"` |

- **GHSA-584q-6j8j-r5pm**: secp256k1-node allows private key extraction over ECDH

## Item 45 — send (LOW)

| Field | Value |
|-------|-------|
| Package | `send@0.18.0` |
| Severity | LOW |
| Advisory IDs | GHSA-m6fv-jmcg-4jfg |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.send = "0.19.0"` |

- **GHSA-m6fv-jmcg-4jfg**: send vulnerable to template injection that can lead to XSS

## Item 46 — serialize-javascript (HIGH)

| Field | Value |
|-------|-------|
| Package | `serialize-javascript@6.0.0` |
| Severity | HIGH |
| Advisory IDs | GHSA-5c6j-r48x-rmvq, GHSA-76p7-773f-r4q5, GHSA-qj8w-gfj5-8c6v |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.serialize-javascript = "7.0.5"` |

- **GHSA-5c6j-r48x-rmvq**: Serialize JavaScript is Vulnerable to RCE via RegExp.flags and Date.prototype.toISOString()
- **GHSA-76p7-773f-r4q5**: Cross-site Scripting (XSS) in serialize-javascript
- **GHSA-qj8w-gfj5-8c6v**: Serialize JavaScript has CPU Exhaustion Denial of Service via crafted array-like objects

## Item 47 — serve-static (LOW)

| Field | Value |
|-------|-------|
| Package | `serve-static@1.15.0` |
| Severity | LOW |
| Advisory IDs | GHSA-cm22-4g7w-348p |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.serve-static = "1.16.0"` |

- **GHSA-cm22-4g7w-348p**: serve-static vulnerable to template injection that can lead to XSS

## Item 48 — sha.js (CRITICAL)

| Field | Value |
|-------|-------|
| Package | `sha.js@2.4.11` |
| Severity | CRITICAL |
| Advisory IDs | GHSA-95m3-7q98-8xr5 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.sha.js = "2.4.12"` |

- **GHSA-95m3-7q98-8xr5**: sha.js is missing type checks leading to hash rewind and passing on crafted data

## Item 49 — simple-git (CRITICAL)

| Field | Value |
|-------|-------|
| Package | `simple-git@3.14.0` |
| Severity | CRITICAL |
| Advisory IDs | GHSA-hffm-xvc3-vprc, GHSA-9w5j-4mwv-2wj8, GHSA-9p95-fxvg-qgq2, GHSA-jcxm-m3jx-f287 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.simple-git = "3.36.0"` |

- **GHSA-hffm-xvc3-vprc**: simple-git is vulnerable to Remote Code Execution
- **GHSA-9w5j-4mwv-2wj8**: Remote code execution in simple-git
- **GHSA-9p95-fxvg-qgq2**: simple-git vulnerable to Remote Code Execution when enabling the ext transport protocol

## Item 50 — tar (HIGH)

| Field | Value |
|-------|-------|
| Package | `tar@4.4.19` |
| Severity | HIGH |
| Advisory IDs | GHSA-9ppj-qmqm-q256, GHSA-f5x3-32g6-xq36, GHSA-8qq5-rm4j-mr97, GHSA-34x7-hfp2-rc4v, GHSA-r6q2-hw4h-h46w |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.tar = "7.5.11"` |

- **GHSA-9ppj-qmqm-q256**: node-tar Symlink Path Traversal via Drive-Relative Linkpath
- **GHSA-f5x3-32g6-xq36**: Denial of service while parsing a tar file due to lack of folders count validation
- **GHSA-8qq5-rm4j-mr97**: node-tar is Vulnerable to Arbitrary File Overwrite and Symlink Poisoning via Insufficient Path Sanit

## Item 51 — tmp (LOW)

| Field | Value |
|-------|-------|
| Package | `tmp@0.0.33` |
| Severity | LOW |
| Advisory IDs | GHSA-52f5-9888-hmc6 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.tmp = "0.2.4"` |

- **GHSA-52f5-9888-hmc6**: tmp allows arbitrary temporary file / directory write via symbolic link `dir` parameter

## Item 52 — tough-cookie (MODERATE)

| Field | Value |
|-------|-------|
| Package | `tough-cookie@2.5.0` |
| Severity | MODERATE |
| Advisory IDs | GHSA-72xf-g2v4-qvf3 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.tough-cookie = "4.1.3"` |

- **GHSA-72xf-g2v4-qvf3**: tough-cookie Prototype Pollution vulnerability

## Item 53 — undici (HIGH)

| Field | Value |
|-------|-------|
| Package | `undici@5.10.0` |
| Severity | HIGH |
| Advisory IDs | GHSA-wqq4-5wpv-mx2g, GHSA-2mjp-6q6p-2qxm, GHSA-r6ch-mqf9-qc9w, GHSA-3787-6prv-h9w3, GHSA-m4v8-wqvr-p9f7 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.undici = "6.24.0"` |

- **GHSA-wqq4-5wpv-mx2g**: Undici's cookie header not cleared on cross-origin redirect in fetch
- **GHSA-2mjp-6q6p-2qxm**: Undici has an HTTP Request/Response Smuggling issue
- **GHSA-r6ch-mqf9-qc9w**: Regular Expression Denial of Service in Headers

## Item 54 — web3-core-method (LOW)

| Field | Value |
|-------|-------|
| Package | `web3-core-method@1.7.5` |
| Severity | LOW |
| Advisory IDs | GHSA-2j4c-9qqq-896r |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.web3-core-method = "?"` |

- **GHSA-2j4c-9qqq-896r**: web3-core-method is vulnerable to prototype pollution

## Item 55 — web3-core-subscriptions (LOW)

| Field | Value |
|-------|-------|
| Package | `web3-core-subscriptions@1.7.5` |
| Severity | LOW |
| Advisory IDs | GHSA-hhf6-3xpg-pggx |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.web3-core-subscriptions = "?"` |

- **GHSA-hhf6-3xpg-pggx**: web3-core-subscriptions has a Prototype Pollution vulnerability

## Item 56 — word-wrap (MODERATE)

| Field | Value |
|-------|-------|
| Package | `word-wrap@1.2.3` |
| Severity | MODERATE |
| Advisory IDs | GHSA-j8xg-fqg3-53r7 |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.word-wrap = "1.2.4"` |

- **GHSA-j8xg-fqg3-53r7**: word-wrap vulnerable to Regular Expression Denial of Service

## Item 57 — xml2js (MODERATE)

| Field | Value |
|-------|-------|
| Package | `xml2js@0.4.19` |
| Severity | MODERATE |
| Advisory IDs | GHSA-776f-qx25-q3cc |
| Dep path | unknown |
| Why no clean fix | Could not trace to a direct manifest ancestor |
| Override recipe | `overrides.xml2js = "0.5.0"` |

- **GHSA-776f-qx25-q3cc**: xml2js is vulnerable to prototype pollution

---

## Decision Required

For the items above, the only mechanical fix is an override.
Reply with package names or advisory IDs to override, or 'none' to leave them unresolved.
