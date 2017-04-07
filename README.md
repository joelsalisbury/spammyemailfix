# spammyemailfix

This is most useful for small sites with static HTML or something you can hook into to appropriately generate mailto links.

* Throw the contents `sf.js`into your `plugins.js` or wherever.
* Make your mailto links like this: `<a href="#" class="spamfree" data-sfname="email" data-sfdomain = "domain.com">Email another me!</a>`
* Also enjoy `addEventListeners`, figured that might be useful.