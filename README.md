# CD-R 700mb is a static music page generator written in "go".
## <img width="625" alt="Screenshot 2023-05-27 at 12 22 27 PM" src="https://github.com/sudo-self/cdr-mixTape-page-creator/assets/119916323/24b138da-5bcb-4e23-9198-09e7b566e164">
### HOW TO
1. Install by running ---> go install github.com/thebaer/cdr/cmd/cdr@latest
2. on mac you can install go with brew. [ brew install go ]
3. Clone this repo git clone https://github.com/sudo-self/CDR-MixTape-Page-Creator/
4. Drop your music files into same folder as the "cdr" executable
5. Make sure they're named in the order you want, and start with a two-digit track number, e.g. `01 - Track 1.mp3`
6. Run `cdr clean` in this directory to standardize the file names based on their metadata (supports ID3, MP4, OGG, FLAC)
7. EXECUTE: /go/bin/cdr/ burn
8. The index.html file will now be in the same folder and you can open it in your web browser
### You can also edit the index.html
10. Copy `mixtape.tmpl` into your mixtape directory
11. Edit this file to your liking, being sure to retain the `{{template ...}}` lines in the file
12. Run `cdr burn` -- it'll generate your page from this template instead of the default! 
### Player + Playlist
### USE IS SOLEY FOR ILLUSTRATIVE PURPOSES ONLY AND SHOULD NOT BE USED TO DISTRIBUTE COPYRIGHTED MATERIAL YOU DO NOT OWN THE RIGHTS TO.

