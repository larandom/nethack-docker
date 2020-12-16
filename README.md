# nethack-docker

NetHack is a wonderfully silly, yet quite addictive, Dungeons & Dragons-style adventure game. 
You play a character from one of many classes (such as wizard, ranger, or tourist), fighting
your way down to retrieve the Amulet of Yendor (try saying THAT one backwards!) for your god.
On the way, you might encounter a quantum mechanic or two, or perhaps King Arthur, or - if 
you're REALLY lucky - the Ravenous Bugblatter Beast of Traal.

alias nethack="docker run --rm -it -v $HOME/.nethack:/var/games/nethack/save larandom/nethack"
