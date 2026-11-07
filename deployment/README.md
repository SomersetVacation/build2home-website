# Connect build2home.au

The domain currently uses Crazy Domains nameservers (`ns1.crazydomains.com`, `ns2.crazydomains.com`). Its website A records were absent when checked on 7 November 2026.

At the domain's DNS provider, configure these **website** records:

| Type | Name | Value |
| --- | --- | --- |
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | SomersetVacation.github.io |

Keep mail/MX/TXT records intact. The public contact is a Gmail address; no new domain email service or MX record is needed for this website.

After the DNS answers correctly:

1. Add a root `CNAME` file containing only `build2home.au` and a newline (the template is in this directory).
2. Set `build2home.au` under this repository's **Settings → Pages → Custom domain**.
3. Verify the DNS check and certificate, then enable **Enforce HTTPS** when available.
4. Verify apex and www redirects plus all support/privacy links.

GitHub recommends account-level domain verification. Use the TXT value GitHub actually supplies under account **Settings → Pages**; do not invent one.

Official instructions: [Managing a custom domain for GitHub Pages](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site).
