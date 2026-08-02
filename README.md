# Murat Yilmazlar

**Vulnerability Researcher & Application Security Engineer** — 10 years of both.

IoT and embedded firmware research (routers · IPTVs · modems · NAS) · application security in e-commerce, fintech, crypto and defence.

The research never stopped, it just moved to nights.

Nothing counts as a finding until a proof of concept runs.

`OSCP` · `OSCE` · `OSWE`

---

### Focus

- **Embedded and IoT** — firmware extraction, reverse engineering, fuzzing, exploit development.
- **Appliance and enterprise web** — infrastructure consoles, and the applications behind them.
- **Application security** — source review for auth, crypto, memory-safety and access-control flaws.
- **AI and LLM security** — prompt injection, RAG poisoning, agent abuse, model supply chain.

---

### Published advisories

| Advisory | Target | Flaw | CVSS | Artifacts |
| --- | --- | --- | :---: | --- |
| [CVE-2020-15568](https://nvd.nist.gov/vuln/detail/CVE-2020-15568) | TerraMaster TOS (NAS) | Pre-auth root code injection in `exportUser.php` (CWE-913) | 9.8 | [module](https://github.com/divinepwner/TerraMaster-TOS-CVE-2020-15568) · [write-up](https://offensive.blog/2021/02/16/firmware-extraction-rce.html) |
| [CVE-2021-30461](https://nvd.nist.gov/vuln/detail/CVE-2021-30461) | VoIPmonitor GUI | Pre-auth RCE via `SPOOLDIR` (CWE-94) | 9.8 | [SSD advisory](https://ssd-disclosure.com/ssd-advisory--voipmonitor-unauth-rce) |
| [CVE-2021-41408](https://nvd.nist.gov/vuln/detail/CVE-2021-41408) | VoIPmonitor GUI | Pre-auth SQL injection via `user` in `api.php` (CWE-89) | 9.8 | [PoC](https://gist.github.com/divinepwner/e51050e0d7df77ff1f1379583e8cf7db) at NVD |

Further advisories are in vendor coordination and cannot be named until they ship.

---

[offensive.blog](https://offensive.blog) · [@divinepwner](https://x.com/divinepwner) · [LinkedIn](https://www.linkedin.com/in/divinepwner) · [murrat@protonmail.com](mailto:murrat@protonmail.com) · [PGP](https://github.com/divinepwner.gpg)
