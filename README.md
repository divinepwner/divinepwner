# Murat Yilmazlar

**Vulnerability Researcher & Application Security Engineer** — 10 years of both.

IoT firmware research (routers · IPTVs · modems · NAS) · appsec in e-commerce, fintech, crypto and defence.

The research never stopped, it just moved to nights.

Nothing counts as a finding until a proof of concept runs.

`OSCP` · `OSCE` · `OSWE`

---

### Focus

- **Embedded and IoT** — taking firmware apart until the exploit lands.
- **Library vulnerability research** — memory-safety flaws in the C/C++ code everything else is built on.
- **Appliance and enterprise web** — the consoles that run the infrastructure, and the applications behind them.
- **Application security** — source review for the flaws that matter, from auth logic to memory safety.
- **AI and LLM security** — offensive research on models, agents, and the systems around them.

---

### Published advisories

| Advisory | CVSS | Target | Flaw | Artifacts |
| --- | --- | --- | --- | --- |
| [CVE-2026-84648](https://nvd.nist.gov/vuln/detail/CVE-2026-84648) | 8.8 | Jenkins core | Stored XSS in system log viewer | [advisory](https://www.jenkins.io/security/advisory/2026-09-02/#SECURITY-3967) |
| [CVE-2020-15568](https://nvd.nist.gov/vuln/detail/CVE-2020-15568) | 9.8 | TerraMaster TOS | Pre-auth root RCE, `exportUser.php` | [module](https://github.com/divinepwner/TerraMaster-TOS-CVE-2020-15568) · [write-up](https://offensive.blog/2021/02/16/firmware-extraction-rce.html) |
| [CVE-2021-30461](https://nvd.nist.gov/vuln/detail/CVE-2021-30461) | 9.8 | VoIPmonitor GUI | Pre-auth RCE, `SPOOLDIR` recheck | [advisory](https://ssd-disclosure.com/ssd-advisory--voipmonitor-unauth-rce) |
| [CVE-2021-41408](https://nvd.nist.gov/vuln/detail/CVE-2021-41408) | 9.8 | VoIPmonitor GUI | Pre-auth SQLi, `api.php` | [PoC](https://gist.github.com/divinepwner/e51050e0d7df77ff1f1379583e8cf7db) |
| [GHSA-4p49-8phx-p9j9](https://github.com/ossrs/srs/pull/4794)     | 8.8 | ossrs/srs | RTCP heap overflow              | []|

Further advisories are in vendor coordination and cannot be named until they ship.

---

[offensive.blog](https://offensive.blog) · [@divinepwner](https://x.com/divinepwner) · [LinkedIn](https://www.linkedin.com/in/divinepwner) · [murrat@protonmail.com](mailto:murrat@protonmail.com) · [PGP](https://github.com/divinepwner.gpg)
