# Meet Live Assist - site

The pages behind https://krystiangw.github.io/meet-live-assist/

| Page | What it is for |
| --- | --- |
| `index.html` | the overview: what it does in a call, who it is for, how to install it |
| `reference.html` | the parts, the full feature list, the markers, the server API |
| `faq.html` | what it does with your meeting, what you need, what to do when it breaks |
| `privacy.html` | the privacy policy, rendered from `PRIVACY.md` in the code repo |
| `sitemap.xml` | submitted to Search Console and Bing; robots.txt on GitHub Pages only counts at the domain root, so it cannot advertise this one |
| `llms.txt` | the same site for agentic crawlers: what it is, and the two things it does not work without |
| `*.txt` (32 hex chars) | the IndexNow key. Bing and Yandex read it to confirm we own the path before accepting a submission; deleting it silently stops those submissions working |

Generated from `docs/` in the extension repo. Edit there and sync, not here: the media and the privacy
page are built by scripts (`tools/media/`) and hand edits would be overwritten on the next sync.
