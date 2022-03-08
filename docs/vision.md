# Pahest
Pahest is born out of an unfulfilled need of true content ownership and
control.

Throughout our digital lives, we produce and publish content. There are myriads
of all-in-one platforms that will happily lure you to use them for producing
and publishing your content: Twitter, Instagram, Writefreely, Facebook,
Diaspora, Mastodon, Wordpress, Tumblr, Medium, Jekyll, Tiddlywiki, the list
goes on and on. As we scatter our content across these different platforms, we
relinquish control and are forced to make a difficult-to-reverse choice that
ties our content to where and how it's stored. When one day Facebook shuts down
or deems you unworthy of expression, all your content stored on Facebook will
disappear. When Wordpress becomes abandoned, you're gonna need to program a
migration script that moves your Wordpress posts from the MySQL database it
uses to the Markdown that Jekyll understands. Data export formats and
facilities are at the mercy of the companies or maintainers of these products.

Pahest believes that this problem can be solved with good old decomposition.
Publishing platforms of today combine 3 essential components: a) content
authoring b) content propagation, and c) content storage. Pahest aims to strip
a well-designed and well-intentioned publishing platform of the concern of
storing content.

## Vision
Pahest is, first and foremost, an open API. It is an API that allows you to a)
publish content, b) manage and control the content and its privacy, and c)
fetch that content.

It allows you to have a single repository where you publish all the content you
produce through an API, and use the API to fetch that content as you need it.
Facebook and Twitter will probably never adopt it, and that is OK--Pahest aims
to create a choice where none exists for those who appreciate the benefits.

Much like something like Jabber, Pahest can be used as a self-hosted service or
a managed one. The non-indexable content may be encrypted to ensure that the
Pahest repository cannot be accessed by anyone with access to the environment
where it operates.

## How will it work
If you have an Instagram-style image blog, a blog about motorcycles, and
another one about programming in Rust, you publish them all into Pahest, and
integrate your blog frontend with the Pahest API so that each blog website
fetches the posts tagged with their topic. Platforms are welcome to cache
content, however your Pahest repository remains the principal source of truth
for your content.

Pahest may or may not integrate with something like ActivityPub.

Pahest may or may not come with its own content authoring tools. In any case,
the best content authoring tools will be made by those who focus on making a
great content authoring tool, and let Pahest manage the persistence.

Pahest repositories will be easily transferable between different Pahest
deployments, self-served or managed. They can be backed up on a tape drive.
They can be passed on to loved ones. After all, they are a pod that contains
your digital life.

All Pahest content will have metadata such as tags and maybe well-specified
fields such as date, title, and description. All Pahest content will be
versioned.

## Final words
Many real problems need to be solved and questions need to be answered to
achieve a usable initial implementation. This document does not aim to cover
any of that, especially since none of it has really been thought through yet.
Instead, this document aims to make Pahest sound like a _good idea_. If it
does, then it's worth implementing and I may spend some more time on it. If it
doesn't, I'm curious why.
