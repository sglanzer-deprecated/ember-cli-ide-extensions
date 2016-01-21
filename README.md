# ember-cli-ide-extensions


sglanzer [11:37 PM] 
So I was looking at the way ember-cli has been creating hubs of components around a concept (like ember-data or ember-cli-deploy)

[11:39] 
We’ve been messing with some IDE extensions, like snippets and more advanced syntax highlighting, I was thinking it would be interesting to try to build an ember-cli hub around IDE extensions, something that could be embedded in an addon, you provide the snippet/etc. and then a consumer installs your addons and the IDE extension for what they’re using and it ​_somehow_​ gets the contents in the right location and format

[11:40] 
So anyone who is writing an addon could basically get IDE integration for cheap with any IDE that had an extension written

ameadows [11:40 PM] 
sounds interesting

sglanzer [11:41 PM] 
I think snippets would probably be an easy start

[11:41] 
ember-cli-ide-extensions

ameadows [11:41 PM] 
my IDE is a little thin, just b/c I don't use a lot of plugins, so I wouldn't really be all that interested in using it (other than the better highlighting bit, that would be nice, although I haven't looked at how good the existing vim highlighting support is for ember)

sglanzer [11:43 PM] 
Yeah, it’s going to vary according to the dev, but that’s the beauty of it being a hub - you would only need to write for the one you care about (brackets in my case) - other people would add their own
