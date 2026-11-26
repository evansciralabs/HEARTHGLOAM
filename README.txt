HEARTHGLOAM
A sound instrument for tabletop role-playing games. One web page, no install, no network, no samples: every sound is synthesized live in the browser. Hearthgloam is a fork of KAIJU-BLUE (build B17.1) by [OWNER LEGAL NAME].

WHAT IS IN THE FOLDER
hearthgloam.html — the instrument. This is the only file you need.
THE BOOK (campaigns, notes, files, dice, table log) is built into hearthgloam.html: the book glyph in the top row opens it full screen over the instrument, and the sound keeps playing.
hg-book.html — the same book as its own page. Optional: open it on its own, e.g. on a laptop beside the table.
1.jpg to 25.jpg (monsters) and 1-1.jpg to 1-25.jpg (scenes) — your monster pictures, when you have them. Optional (see PICTURES). Without them each monster shows its own card.
README.txt, GUIDE.txt (how to use it at the table), LICENSE.txt.

RUNNING IT
Open hearthgloam.html in a current browser (Chrome, Edge, Safari or Firefox), or put the folder on any static web host. On phones, use HTTPS hosting: motion sensors (LANTERN) and MIDI only work on a secure page.
Tap the power button (top left) to start. Browsers only allow sound after a tap.
Start with your speaker turned down. A limiter holds the output at -1 dBFS, but a monster can still be loud.

PICTURES
Until you add art, each of the 25 monsters shows its own card: a sigil for its kind (fire, sea, frost, wild, arcane, undead, stone), its number and its name. No picture files are needed.
To bundle your own art with the page, put it next to hearthgloam.html:
1.jpg to 25.jpg: the monster, portrait (the number is the monster's number). Keep the monster in the centre.
1-1.jpg to 1-25.jpg: the wide scene for landscape screens (1-N goes with monster N). Leave the middle for the monster.
The old KAIJU-BLUE files (1.jpg to 24.jpg) are no longer used; you can delete them.
Or load pictures at the table: the compass, TABLE, ART: PORTRAIT (pick several at once to fill this monster and the next ones) and ART: LANDSCAPE. A portrait loaded this way also chooses that monster's sound from its colours; see GUIDE. That art stays in that browser on that device. ART: RESET goes back to the card.
Use your own original artwork.

PROJECTOR AND A SECOND DEVICE (LINK)
For a group: one device on the projector (the Scene device), the game master's own phone or tablet in hand. The game master's choices reach the Scene device by light, not by network: SEND shows the table as a QR code, and the Scene device's camera reads it (WATCH). See GUIDE, THE PROJECTOR. The camera only opens on a secure page: host the folder on HTTPS (or open it on the same computer). A page opened as a file, or over plain http from another device, cannot use the camera.

SYSTEM (double-tap the eye)
Breaks with the pond, battery saver, the network kill switch, the colour of the table, and the room meter. See GUIDE.txt, PART FOUR.

PRIVACY
Nothing is sent anywhere. The page's security policy blocks every network request. LINK uses the camera only while WATCH is on; frames are read on the device and never stored or sent. The ROOM meter uses the microphone only while METER is on; it measures level and keeps nothing else. Settings, scenes, the book, your own art, the party's pictures and your maps stay in this browser on this device (storage names starting hg_, and the browser's IndexedDB). Clearing the browser's site data clears them. Use the book's BACKUP to keep a copy of your campaigns; keep your own copies of any pictures you load.

WHAT HAS NOT BEEN CHECKED
The builder measured levels, timing and layout in a headless browser, and tested LINK end to end with a simulated camera. It could not listen, and it could not test real phones, real cameras or microphones, projectors, speakers, Bluetooth or MIDI controllers, or battery life. Try a session at home before game night, and try LINK across the room you'll play in.

LICENSE
See LICENSE.txt.
