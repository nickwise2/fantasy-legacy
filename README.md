# FantasyLocker website

Public landing page, privacy policy, support, terms and import guide.

- Production: https://fantasylockerapp.com/
- GitHub Pages source: `main:/docs`
- Preview: `python3 -m http.server 8766 --directory docs`
- Current install destination: https://testflight.apple.com/join/UJsd7ccg

After the public App Store release is verified, replace the three beta links and beta availability copy in `docs/index.html` with the verified App Store product URL. Do not advertise public availability before release.

No analytics scripts, external fonts, cookies or build dependencies are added by this site. Preserve `assets/fantasylocker-email.png`: transactional emails reference it.

Domain DNS is managed in Porkbun. Web routing must not alter the support-forwarding MX/SPF or Resend DKIM, `send` and `rsend` records.
