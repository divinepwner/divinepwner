
# Murat Yilmazlar

**Vulnerability Researcher & Application Security Engineer** — 10 years of both.

IoT and embedded firmware research (routers · IPTVs · modems · NAS) · application security in e-commerce, fintech, crypto and defence.

The research never stopped, it just moved to nights.

Nothing counts as a finding until a proof of concept runs.

`OSCP` · `OSCE` · `OSWE`

---

### Focus

**Embedded and IoT** — firmware extraction and emulation, binary reverse engineering, coverage-guided fuzzing, crash triage to PC control. The device, not the datasheet.

**Appliance and enterprise web** — the consoles that manage infrastructure and the applications that run the business. One ships inside a product nobody owns; the other has a whole team and still gets access control wrong.

**Application security** — source review for authentication, cryptographic, memory-safety and access-control flaws. SAST and SCA in the pipeline, bug bounty programmes built and run end to end at three companies. Design review while a system is still text and there is nothing built to defend.

**AI and LLM security** — prompt injection and jailbreaks, RAG poisoning and cross-tenant exfiltration, agent and tool-calling abuse, model supply chain and inference infrastructure. The failures live at the boundaries, not in the model.

---

### Published advisories

| Advisory | Target | Flaw | CVSS | Artifacts |
| --- | --- | --- | :---: | --- |
| [CVE-2020-15568](https://nvd.nist.gov/vuln/detail/CVE-2020-15568) | TerraMaster TOS (NAS), before 4.1.29 | Unauthenticated code injection executing as root, via dynamic class method invocation in `include/exportUser.php` (CWE-913) | 9.8 | [Metasploit module](https://github.com/divinepwner/TerraMaster-TOS-CVE-2020-15568) · [write-up](https://offensive.blog/2021/02/16/firmware-extraction-rce.html) |
| [CVE-2021-30461](https://nvd.nist.gov/vuln/detail/CVE-2021-30461) | VoIPmonitor GUI, before 24.61 | Unauthenticated remote code execution via the `SPOOLDIR` value in the recheck option (CWE-94) | 9.8 | [SSD advisory](https://ssd-disclosure.com/ssd-advisory--voipmonitor-unauth-rce) |
| [CVE-2021-41408](https://nvd.nist.gov/vuln/detail/CVE-2021-41408) | VoIPmonitor GUI, up to 24.61 | Unauthenticated SQL injection via the `user` parameter in `api.php` (CWE-89) | 9.8 | [PoC](https://gist.github.com/divinepwner/e51050e0d7df77ff1f1379583e8cf7db) cited by NVD |

Further advisories are in vendor coordination and cannot be named until they ship.

---

[offensive.blog](https://offensive.blog) · [@divinepwner](https://x.com/divinepwner) · [LinkedIn](https://www.linkedin.com/in/divinepwner) · [murrat@protonmail.com](mailto:murrat@protonmail.com) · [PGP](https://github.com/divinepwner.gpg)
