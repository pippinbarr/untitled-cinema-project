# Process journal

## Opening salvo (16-04-2021 14:06)

This is just a chance to write a few thoughts down about what I'm thinking about with this game. The major overall idea is to create a game environment that forces/encourages the player to watch a movie. So a kind of Trojan Horse affair where the player thinks they're playing one kind of game (an assassination kind of exciting spy thing) but in fact the excitement of that game never comes to pass and they just spend their time watching the movie.

Here are a couple of key areas of thought I'll need to address and expand on I assume

### Technology

This idea initially came about with the idea of a really simple UI that would be the movie itself, ideally a fixed camera no-cuts film of something like an opera or ballet performance, with an overlay of a sniper scope or similar. The player would sit there moving the scope around and receiving instructions, but would never get the okay to fire (and would lose if they did). This could be accomplished in plain JS on a webpage if I found the right movie.

(By the by, I tested the absolute basics of getting a film from archive.org playing on a webpage and it was fine, so I think this is technically very doable.)

The alternative I've been entertaining is to do something actually set in a cinema, so there's literally a movie playing and the narrative frame is around needing to assassinate someone in the theatre. Again with some kind of handler who controls your ability to identify the person and act, never giving the signal. The latter is presumably the "really cool one" while the former is the "way fucking easier one".

(It's more notional whether/how easily I can get a full length movie playing here. I kind of assume I can stream it from archive.org but might run into CORS or other issues. If it were downloadable I could include the movie itself with the download, though that would massively balloon it of course.)

### Agency

In the cinema version there are potential implied issues around freedom of movement and action for the player. At the heart of this is needing to prevent or discourage the player from just shooting random people or acting out - they need to wait. Clearly you can just have them lose instantly if they act incorrectly and that may just be the best option, a kind of "that's not what happened" instant cut if they fire the gun (ever). "Snaaaaake!" fission mailed.

The more they can walk around the more weird it would get in the cinema because they'd be fucking annoying to everyone, but can you reasonable just force them to just sit there? I mean mechanically speaking of course you can, but can you keep them engaged that way? Maybe you can send them out to a bathroom at some point to get a gun? Stuff like that? Little tasks that build up but don't result?

Could do 3D but position the player in a projection box or other space so that they're locked into just looking through a scope at the cinema?

Could even *let* them shoot the target at the end of the movie as everyone is leaving which would be pretty fucking funny, and you just win at that point.

### Fidelity

How realistic does it need to be? In the 2D version I guess you can work on matching the UI to the grain of the film etc. to try to make it look as authentic as possible within that very simple framing.

In the 3D version it's going to be a bit of a Robert Yang nightmare to try to produce a realistic cinema and people in it with their behaviours etc. So at best it needs to be low poly. There is a low poly cinema buyable on the Asset Store and I'd almost certainly prioritize buying assets over anything else. (By the way the search for cinema assets has triggered a desire to produce a game made of cinemas, maybe a horror game?)

### Movie tie-ins

I like the idea of even thinking about this as being more specifically related to the film (perhaps particularly in the 3D version?) That the person handling you/talking to you (sending you texts?) could be referring to things that literally happen in the movie, maybe tying them into the outer story the game is telling? Maybe referring to specific events in the film to look out for as part of the project of assassination (and this vaguely makes me wonder if there could be some other aim, but that original idea of watching a movie specifically through a sniper scope seems to great to me so I don't quite know).

### Well

Basically I think there's a lot to like here, but some major decisions to be made along with that. I guess I could try making both the 2D and 3D versions separately. Or you could play the 2D version inside the 3D version while killing time ha ha.

There's an element of airplane mode here, but I think there's something about the "killer's gaze" directed at a film that's really interesting. Also shades of something like Pulp Fiction, killers doing ordinary things while waiting to do terrible things.

---

# Let the game fit the available creative commons video (19-04-2021 11:16)

Something that is kind of making some decisions for me is the availability of appropriate video for the 2D context discussed above. I'm simply not finding a whole lot of statically framed, no-cuts video of... anything at all. In my dreams there would have been all these recordings of operas from a tripod, but the reality is that those things don't appear to be out there to the extent my searching has been able to find them.

Whereas there definitely is availability of Old Movies. Soooo, it's kind of looking like I have to return to Unity and create a movie theatre scenario. I'm a little afraid because that sounds like quite a large project, but on the other hand is *is* quite an interesting things to work on in that so much of what will need doing is kind of traditional game stuff, since the game is trying to look and feel like a proper exciting game, while actually not being that. (Now that I mention this I'm vaguely thinking about *A Hand With Many Fingers* as an inspiration point here.)

Well then oh boy. So how do I make some headway into this?

* Get the latest Unity for the millionth fucking time
* Worry about it playing nice with the M1 in this new computer
* Investigate playing a CC film inside the engine both for application and WEBGL versions
* Buy a cinema (there's that low poly one which is a touch gross, but may be the best bet)
* Play the movie in the cinema

Why I am I writing a to do list inside my process journal?

Well at any rate those are the first few steps in what could turn out to be a pretty fucking painful process. A couple of early thoughts...

* I'm likely to be quite constrained by the nature of the cinema asset I download because I don't think(?) I want to drill down to the level of modelling my own stuff, which in turn means being kind of stuff with whatever is there (like if I want a bathroom scene and there's no bathroom then there's no bathroom scene). There could be some interest in that, or it could be "ruined"?
* There are aesthetic constraints too. I need to have people in this world and they then need to match the architecture of the cinema (in terms of resolution, palette, etc.) which is another light nightmare
* Should I be trying to make a cinema in Pro Builder so that I can control everything? Is that just asking for trouble or is that a way to train myself more deeply in things that I may well want to use in the future? Could go for some kind of Super Hot minimalism in terms of texturing etc., or at least flat textures to avoid going mad? Do I want to do that? Maaaaaybe. Maybe. I don't really know.
* There are just many spiralling implications here. I think it's worth buying the cinema first regardless as a place to stage things, and then if I need to make my own to feel good about things I can do that separately afterwards. Maybe this is just a game that will take a while to make and I can be okay with that?
* I'll need to watch the film I choose because I think I do like that idea of the handler making comments about the film as it goes along either through an earpiece or as they sit there behind you, that can feed into the adaptation part of things (maybe it could even be some lame film crit. "this reminds me of x")

Okay well, we have some steps to take. Including starting a proper to do document and writing the first why draft.
