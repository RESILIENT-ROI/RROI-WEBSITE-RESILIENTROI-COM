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
| 018-2026-SEP-23 | <b class="dbj_yellow">doing</b> | Services first, DBJ Method out of the front (DBJ ruling). [hugo.toml](../hugo.toml): About section and its nav link off (it repeated the services); hero sentence on the method removed; hero button now "What We Do" → #projects; site description is "Safety at AI Speed." The method stays in the footer terms and behind the services' "Read more" links. Dropped with About: the 3QF line and "Human-led". DBJ to check on localhost |
| 011-2026-SEP-23 | <b class="dbj_green">done</b> | Git commit and push, done by DBJ |
| 013-2026-SEP-23 | <b class="dbj_green">done</b> | Status colours: `<style>` block added at the top of this file (VS Code preview cannot reach `.vscode/` CSS from here). DBJ confirmed colours show |
| 017-2026-SEP-23 | <b class="dbj_green">done</b> | Service cards showed broken image placeholders. Override [layouts/partials/sections/projects.html](../layouts/partials/sections/projects.html) skips the image when a card has none. Checked on localhost after restart: four cards, no placeholders, Recent Posts gone |
| 016-2026-SEP-23 | <b class="dbj_green">done</b> | Recent Posts off the home page (`recentPosts.enable = false`). Logo working posts moved by DBJ from `content/posts/` to `.ideas/` (unpublished, source files kept) |
| 015-2026-SEP-23 | <b class="dbj_green">done</b> | Post images broken in home page Recent Posts (relative paths). Fixed with absolute paths in [logoptions](../content/posts/logoptions/index.md) and [logo-subversion-10](../content/posts/logo-subversion-10/index.md); checked on localhost: all images load |
| 010-2026-SEP-23 | <b class="dbj_green">done</b> | Local check: DBJ ran `hugo server --minify` (Hugo 0.157.0 extended, 15 pages, clean); CWR read the page in the browser pane: hero, About, four services and Contact render; all 11 links correct |
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
