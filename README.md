# Meet Live Assist - old address

The site moved to **https://meet-live-assist.github.io/** and its own organisation.

Google assigns one site name and one favicon **per hostname**, never per subdirectory, so every page under
`krystiangw.github.io/` inherited the name and icon of the site that owns that host's root. A product page
signed with an unrelated site is worse than no page.

What is left here is four redirect stubs: a `canonical` at the new address, an immediate `meta refresh`, and
`noindex, follow` so the old URLs drop out of the index while still passing the link on. GitHub Pages cannot
return a 301 for a project path, which is the only reason this is not one.

`index.html` keeps the Search Console verification tag. Removing it would drop the old property, and the old
property is how the migration gets watched.
