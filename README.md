I want to use Frontmatter to get a subset of the entries in mainSections (so they appear on top page)

This repo shows /events filtered by metadata:  

* Upcoming events on top (with images)
* Past events on below that (without images)

The above is done with this template:

https://github.com/thunderrabbit/barefoot_rob/blob/events/themes/purehugo-augmentation/layouts/events/list.html

I want events to be the top page of my site, so
I put `events` into mainSections, and the top page shows events using this template

https://github.com/thunderrabbit/barefoot_rob/blob/events/themes/purehugo-augmentation/layouts/index.html

It looks like maybe two where clauses would do it: (where in mainSections) (where frontmatter date < today) but I could not figure out how to do them.

How can I get the top page of this repo to look like the /events page of this repo?
