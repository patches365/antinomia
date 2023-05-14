Antinomia: Final Fantasy VI - v1.0 - Fast Moon

======================
BACKGROUND
======================

Antinomia (n.) - Two principles equally valid but diametrically opposed.

The intent of this hack is to elevate General Leo to a deuteragonist role and periodically shift the narrative focus from the main party to him, in order to explore the events on the Imperial side in parallel with the main casts' actions (kind of like what FF8 did with Laguna).  The narrative split continues until Leo and the Returners' stories intersect, at which point more substantial changes occur, such as Leo surviving and eventually being able to join the party as a permanent member, and the World of Ruin's story progression being retooled.  The overall story and mechanics remain mostly the same, but utilize an expanded ROM and dialogue bank for dozens of new cutscenes and events to expand upon what's already there, for all characters, not just Leo.

This is first and foremost a story hack rather than a gameplay hack.  Not to "change" the story, so much as tell it from a different set of eyes, and to give my favorite character a chance to participate in that story more than he did originally.  There are a few new boss fights and some minor adjustments to battle mechanics, as well as a few events that utilize mechanics not present in the original game.  But expanding on the original world, characters, and themes while still remaining loyal to them was my goal going into this rather than changing the manner in which the game is played. As such, no characters have been added, replaced, removed, or significantly altered, with the exception of Siegfried, since he served no purpose in the original game and I wanted to utilize his sprite memory for something else, so he no longer exists.  So if you're a die-hard Siegfried fan, this hack is not for you.

FF6Hacking.com thread: https://www.ff6hacking.com/forums/thread-4047.html

======================
INSTALLATION
======================

- Base ROM: Final Fantasy III (U) (V1.0).  You are responsible for finding this yourself.
- Use a tool such as Lunar IPS or SNEStuff to apply the IPS patch to the original ROM.
- Alternatively, place the original base ROM and the IPS file in the same folder and name them both the same thing: i.e, "Antinomia_Final_Fantasy_VI.ips" and "Antinomia_Final_Fantasy_VI.smc".  Many emulators such as SNES9x will automatically combine the files when the base ROM is loaded.
- If you don't know whether your base ROM is headered or unheadered, the file size of an unheadered ROM is 3072KB, while a headered is 3073KB.  Alternatively, if you open the ROM in a hex editor, if it's headered you'll see a bunch of 00's for the first 0x200 addresses.
- You'll probably get a "bad checksum" error when loading the patched ROM, which is typical with patches, but take note of the 8-digit CRC32 the emulator provides and compare it to the one provided in the change log below to ensure that everything merged as expected.
- Definitely not compatible with any patches that alter game dialogue due to this hack using custom dialogue addressing.
- Your mileage may vary on patches that alter game mechanics, depending on what memory was altered.

=====================
NEW FEATURES
=====================

- Leo's sprite recolored to more closely match his menu portrait
- Leo can now become a permanent party member... OR NOT, depending on player choices.
- Mog is now a temporarily-recruitable guest character to open a permanent slot in the roster for Leo.
- Two new events added to the World of Balance featuring Leo as a playable guest character, along with adding him to a third where he wasn't originally present.
- Brand new intro event to the World of Ruin
- Brand new re-recruitment event for Leo in World of Ruin to obtain him as a permanent party member
- Shadow becomes permanently recruitable in the World of Balance
- Over an hour's worth of new or expanded cutscenes, with over 800 new lines of dialogue
- New retranslation of much of the original script.  Woolsey was used as a base and his translation was kept for lines that were "close enough" or whose localization didn't detract from the original intent.  The remainder of the script has been relocalized and refreshed.  This is an original retranslation, not one from previous mods.
- Spell, item, monster, and ability names updated to be consistent with modern naming schemes in the series, provided there were enough characters to fit the name (e.g., even though "Firaga" will fit in 6 letters, "Blizzaga" and "Thundaga" will not, so for consistency's sake, they have all remained "Fire 3", "Ice 3", and "Bolt 3").
- Evasion glitch patched. The Goggles no longer do nothing.
- Dance never fails
- Desperation attacks much easier to trigger
- Several new pieces of music
- New sidequest for additional stat gains
- New ultimate weapon sidequests

====================
CHANGE LOG
====================

----
v1.0 [CRC32: D4CB44B0]
----
Bugfixes
- Opening dialogue with Biggs and Wedge was not auto-advancing
- Event in Leo's South Figaro scenario was warping focus back to the Returner's Hideout
- Shadow permanent recruitment event was triggering prematurely
- Fixed Interceptor's walk speed during Shadow recruitment event
- Some children's dialogue branches had been erased during Terra's WoR event
- Fixed Leo's NPC sprite appearing when it wasn't supposed to
- Fixed Celes facing the wrong direction during Nikeah event
- Fixed character walk speed during Celes Solitary Island event
- Text formatting on multiple-choice dialogue boxes fixed
- Text formatting on centered text dialogue boxes fixed
- "SwdTech" changed to "Bushido" in the menus to match the battle command

Known Bugs
- Due to being moved to the Guest slot, Mog no longer has a riding sprite, so making him the party lead and putting him on a chocobo or Magitek armor (Cyan's dream) will cause him to turn into a pink Banon when faced sideways. I don't have a way to fix this as the Guest slot has no sprite entry for riding (this issue already existed in vanilla).
- Some of the character or camera movement speeds are inconsistent in a few cutscenes. May fix this in a later release.

====================
CREDITS
====================
Writing and Coding:
	Fast Moon
Translation and Localization:
	Ted Woolsey
	Fast Moon
Additional Music:
- "Moogle Music Box", "Terra's Theme (Piano)" Arrangement:
	Fast Moon
- "Leo's Flashback - The Monster in the Lab" Composition and Arrangement:
	Fast Moon
- "Dancing Calcobrena", "Battle on the Big Bridge", "Home, Sweet Home", "Hurry! Hurry!", "Library of Ancients", "Spreading Grand Wings"
	emberling
- "Into the Darkness"
	MetroidQuest
- "Melody of Lute", "Troian Beauty", "Red Wings"
	Gi Nattak
Hacking Tools/Utilities:
- FF3usME (sprite editing, item editing, monster editing)
	Lord J
- FF6LE CE (map editing, NPC editing, event trigger editing)
	Lord J
	madsiur
- FF3DE (dialogue editing)
	Fast Moon
- Tinymm (convert MIDI to MML for music editing)
- RS3ExTools2 (convert MML to FF6 music data)
- HxD (hex editing of events and game code)
- Lunar IPS (IPS patch file generation)