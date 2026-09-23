---
version: 0.5
# status markup, copy verbatim into the status column:
#   <b class="dbj_red">tbd</b>
#   <b class="dbj_yellow">doing</b>
#   <b class="dbj_green">done</b>
statuses:
  - tbd
  - doing
  - done
---

<style>
b.dbj_red, b.dbj_yellow, b.dbj_green { color:#000; padding:1px 6px; border-radius:3px; white-space:nowrap; }
b.dbj_red { background:#f4a6a6; } b.dbj_yellow { background:#f7e27a; } b.dbj_green { background:#a8dca8; }
</style>


| UID_TIMESTAMP | status | comments |
|---|---|---|
| 011-2026-SEP-23 | <b class="dbj_red">tbd</b> | Git commit and push; nothing committed yet. CWR reminds DBJ |
| 010-2026-SEP-23 | <b class="dbj_red">tbd</b> | Local check with `hugo server --minify` at localhost:1313. CWR cannot run it on ws01dbj until the Windows update fix is installed. CWR reminds DBJ |
| 013-2026-SEP-23 | <b class="dbj_yellow">doing</b> | Status colours: `<style>` block added at the top of this file (VS Code preview cannot reach `.vscode/` CSS from here). DBJ to confirm colours show |
| 009-2026-SEP-23 | <b class="dbj_green">done</b> | ASH and ZED not added (DBJ ruling). Roster stays ALL, human:DBJ, RROI_SITE, CWR |
| 008-2026-SEP-23 | <b class="dbj_green">done</b> | 3QF line added to About: scalability, resilience, compliance → [dbj.org/3qf-the-key-to-roi](https://dbj.org/3qf-the-key-to-roi/) |
| 007-2026-SEP-23 | <b class="dbj_green">done</b> | About in plain words, one link per method term (Taxonomy, operating model, maturity model, the wheel). "Deterministic Execution" folded into "Business declares, technology implements" |
| 006-2026-SEP-23 | <b class="dbj_green">done</b> | Old three services removed from [hugo.toml](../hugo.toml): Legacy Modernisation and AI-Speed Architecture merged into the new services; Architectural Audits became "Maturity Assessment" → [method.dbj.org/cmm](https://method.dbj.org/cmm/index.html). DBJ approved |
| 005-2026-SEP-23 | <b class="dbj_green">done</b> | Three new services in [hugo.toml](../hugo.toml), plain language, each with a "Read more" button: Organisation Enablement → [method.dbj.org/cmm](https://method.dbj.org/cmm/index.html); Knowledge Preservation → [iceberg.dbj.org/kb/technical-debt](https://iceberg.dbj.org/kb/technical-debt/); Method Chapters → [method.dbj.org](https://method.dbj.org/). Old three kept below them until 006 |
| 012-2026-SEP-23 | <b class="dbj_green">done</b> | `dbj_tbd.html` at repo root deleted by DBJ, replaced by this file |
| 004-2026-SEP-23 | <b class="dbj_green">done</b> | Contact email set to info@resilientroi.com in [hugo.toml](../hugo.toml) |
| 003-2026-SEP-23 | <b class="dbj_green">done</b> | Fresh `.colocuting/`: `to` v0.2.0, README, names, empty transcript |
| 002-2026-SEP-23 | <b class="dbj_green">done</b> | [CLAUDE.md](../CLAUDE.md) rewritten for hugo-profile (was PaperMod) |
| 001-2026-SEP-23 | <b class="dbj_green">done</b> | [hugo.toml](../hugo.toml) copy: hero, About / Method, Services (interim), Contact; UK spelling (en-gb) |

---
<br/>
<br/>
<br/>
<br/>
DBJ_VERTICAL_KANBAN | &copy; 2026 by dbj@dbj.org | MIT License
