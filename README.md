# Music Playlists for Just Natsuki

A fan-made custom music playlist submod for [Just Natsuki](https://github.com/Just-Natsuki-Team/NatsukiModDev), built in Ren'Py 6.99 because someone (me) knew there had to be a better way than stitching a dozen songs together like some horrible human centipede made out of mp3s. I mean, I'd have settled for that if I could keep the music notifications. By the way, I fixed those too. That's a different submod. We'll get to that.

---

> [!WARNING]
> **This is an unofficial fan-made submod for Just Natsuki. It is not affiliated with the Just Natsuki team.**  
> The developers are **not responsible for troubleshooting this submod** or problems caused by installing it.  
>
> > Before installing, **please back up your persistent data:** [How to back up your JN persistent file](https://github.com/Just-Natsuki-Team/NatsukiModDev/wiki/04:-FAQ#can-i-back-up-my-save-data--how-do-i-find-my-persistent)

*Seriously please for the love of god it takes like zero effort, just back up your persistent file (it is a really good habit)*

---

## What is this?

**Music Playlists** adds playlist support to the custom music system. Instead of only picking one loose custom track at a time, you can now give Natsuki a folder full of songs and a `playlist.txt` file that tells her:

- what order to play the songs in
- how long each song is
- what display name to show
- when to move to the next track

**Why do any of that with a text file?** Because Ren'PY 6.99 is *dumber than a sack of wet hammers*, that's why!

---

## Features

**Music Playlists** includes:

- "set and forget" folder-based playlist management
- your usual support for `.mp3`, `.ogg`, and `.wav`
- optional support for my *Fix Music Notifications* submod
- a custom playlist icon/graphic to make playlists subtly stand out in the music picker
- simply leave 'playlist mode' by opening the music menu and choosing literally anything except "nevermind"
- macOS-friendly path handling through JN's existing custom music system (I can hear all four of you rejoicing)
- and an...

### Included demo playlist

As a template, this release includes a `custom music` playlist containing:

- **9 copyright-free songs** hand-picked for a whole bevy of Natsuki vibes
- **playlist.txt** file that does double-duty as a complete tutorial on making your own playlists
- **track-licensing.txt** that I spent *hours* on to demonstrate that "copyright-free" claim

The included tracks are ready to use as a working example playlist. Since the JN vanilla code ignores folders in the "custom_music" folder, this means tracks you place into playlist folders are separate from the regularly-selected tracks. (If you want Natsuki to randomly pick one sometime, just keep a copy of that song in "custom_music".) You can use the supplied Music Playlists tracks as-is, swap me out, rename the playlist, or build your own playlist once you know what you're doing and you're ready to rev up your own Natsuki Radio. 

Huh. Maybe _that's_ what I should've called this submod...


### Bonus: Natsuki won't fight you for the AUX cable

Yeah I thought of that. This submod blocks JN's automatic random music changes, but only while a playlist is active (and Natsuki will tell you this upfront). Outside of playlist mode, the player's normal _Just Natsuki_ music settings are respected. This was a lot of work to make happen and I'll accept gluttonous accolades anytime, day or night.

___

## Installation

1. Back up your persistent file.

2. Download the latest release.

3. Copy everything inside the release's `game` folder into your Just Natsuki `game` folder.

4. Copy everything inside the release's `custom_music` folder into, you guessed it, your Just Natsuki `custom_music` folder.

5. Launch "Just Natsuki" and give her a little compliment. Girl deserves it.

6. Ask Natsuki to change the music.

7. Pick the playlist entry from the music menu.

8. Enjoy the sweet tunes.

9. Now read "playlist.txt" and go forth. I am a river to my people.


---

## Bug reports

If you run into a bug, ~get the Raid can~ please log an issue saying as much of this as possible:

- what happened
- what you were doing right before it happened
- whether you were playing a playlist, loose custom track, built-in track, default music, or no music
- the contents of your `playlist.txt`
- the traceback, if the game threw one
- your operating system
- what other submods you have installed

Basically, as always, bring receipts.

---

## Credits

- Team Salvato for Doki Doki Literature Club
- The Just Natsuki Team for their work on Just Natsuki
- The musicians and sources credited in `custom music/track-licenses.txt`, you folks are the best
