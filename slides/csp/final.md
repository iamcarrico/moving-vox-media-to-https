
```
content-security-policy:
  default-src https: data: 'unsafe-inline' 'unsafe-eval';
  child-src https: data: blob:;
  font-src https: data:;
  img-src https: data:;
  media-src https: blob:;
  script-src https: data: blob: 'unsafe-inline' 'unsafe-eval';
  style-src https: 'unsafe-inline';
  block-all-mixed-content;
  upgrade-insecure-requests;
  report-uri https://vox.report-uri.io/r/default/csp/enforce
```

Note:

This is what we end up with (slightly abridged to fit on the slide).
