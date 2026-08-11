# Meet Live Assist - old address

The site moved to **https://meet-live-assist.github.io/** and its own organisation.

Google assigns one site name and one favicon **per hostname**, never per subdirectory, so every page under
`krystiangw.github.io/` inherited the name and icon of the site that owns that host's root. A product page
signed with an unrelated site is worse than no page.

What is left here is four redirect stubs: a `canonical` at the new address and an immediate `meta refresh`.
GitHub Pages cannot return a 301 for a project path, which is the only reason this is not one.

There is deliberately **no `noindex`** here. It was in the first version and it was a mistake: Google's own
canonicalization guidance says not to use `noindex` for this, because the signal can be consolidated onto the
canonical target. The old URLs were never indexed, so the only thing `noindex` could have achieved was
teaching Google not to index the new address.

`index.html` keeps the Search Console verification tag. Removing it would drop the old property, and the old
property is how the migration gets watched.
