# FantasyLocker website

Public landing page, privacy policy, support, terms and import guide.

- Production: https://fantasylockerapp.com/
- GitHub Pages source: `main:/docs`
- Preview: `python3 -m http.server 8766 --directory docs`
- Current install destination: https://testflight.apple.com/join/UJsd7ccg

After the public App Store release is verified, replace the three beta links and beta availability copy in `docs/index.html` with the verified App Store product URL. Do not advertise public availability before release.

No analytics scripts, external fonts, cookies or build dependencies are added by this site. Preserve `assets/fantasylocker-email.png`: transactional emails reference it.

Domain DNS is managed in Porkbun. Web routing must not alter the support-forwarding MX/SPF or Resend DKIM, `send` and `rsend` records.

## Platform coverage

Checked against the build 128 app source and live provider catalog on October 26, 2026. Beta import connections: Sleeper, Fleaflicker, MyFantasyLeague, Fantrax and Fantasy Premier League. Yahoo Fantasy, ESPN, CBS Sports and NFL Fantasy account connections remain unavailable. Keep the homepage, import guide and support page aligned when availability changes. A listed connection does not imply identical history depth or commercial/provider approval.
