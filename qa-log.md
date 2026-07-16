# Online QA — 2026-07-16

- Stable deployment: https://inverness-custom-tours-mobile-demo.pages.dev/
- Tested full-page layouts: 360×800, 390×844 and 1440×900 in Microsoft Edge via Playwright. No clipping, overlap or horizontal overflow observed.
- Online response: 200; HTML meta robots is `noindex,nofollow`; response header is `X-Robots-Tag: noindex, nofollow`.
- Current official website link returned 200.
- Email and phone links use verified public contact data.
- Concept-preview boundary and non-guarantee language are visible in the contact section and footer.
