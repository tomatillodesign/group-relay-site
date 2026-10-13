# group-relay.org: landing page

The public one-page site for Group Relay (what it is, why you got an email, how to leave,
how to report abuse) plus `privacy.html`. Served by GitHub Pages. The service itself lives in
the private `group-relay` repo; the admin app runs at app.group-relay.org.

- `index.html`, `privacy.html`: the pages. `styles.css` and `favicon.svg` started from
  message-relay.org's and were recolored (green accent `#2f5d50`) so the two read as siblings.
- `404.html`: a copy of `index.html`. **Re-copy it after any edit to `index.html`.**
- `CNAME`: custom domain group-relay.org.

## Status

- [x] Pages built, Oct 13, 2026
- [x] GitHub repo (public; Pages needs it), Pages on (main, `/`), Oct 13: https://tomatillodesign.github.io/group-relay-site/
- [ ] Hover DNS: apex A → 185.199.108.153 / .109.153 / .110.153 / .111.153 (replacing Hover
      parking 216.40.34.41); delete the wildcard `*` A; `www` CNAME → `tomatillodesign.github.io`.
      **Leave MX, bounce, _dmarc, app and the DKIM CNAMEs alone.**
- [ ] Custom domain set in Pages, HTTPS enforced
- [x] hello@ and privacy@ forward to Chris like postmaster@ and abuse@ (group-relay repo, Oct 13)
