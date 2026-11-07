# Connect build2home.au

The domain uses Crazy Domains nameservers (`ns1.crazydomains.com`, `ns2.crazydomains.com`). On 7 November 2026 all four apex A records were saved and verified in public DNS. The old www parking A record was replaced with the CNAME below. GitHub Pages has the custom domain and the repository root CNAME file.

At the domain's DNS provider, configure these **website** records:

| Type | Name | Value |
| --- | --- | --- |
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | SomersetVacation.github.io |

Keep mail/MX/TXT records intact. The public contact is a Gmail address; no new domain email service or MX record is needed for this website.

Remaining deployment verification:

1. Confirm the www CNAME has propagated alongside the apex records.
2. Verify the certificate, then enable **Enforce HTTPS** when available. Last checked: not enforced and HTTPS certificate did not yet match build2home.au; do not bypass browser warnings.
3. Verify apex and www redirects plus support/privacy links and desktop/mobile visual layout. Static checks pass, but the latest layout change still needs browser verification because localhost preview was unreachable and the custom-domain certificate was pending.

GitHub recommends account-level domain verification. Use the TXT value GitHub actually supplies under account **Settings → Pages**; do not invent one.

Official instructions: [Managing a custom domain for GitHub Pages](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site).
