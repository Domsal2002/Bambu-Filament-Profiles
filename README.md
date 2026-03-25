# Bambu Lab Filament Profiles
A collection of tested filament profiles for Bambu Lab printers. Currently focused 
on the H2D but contributions for other Bambu machines welcome.

Although these profiles are tuned on an H2D, they should serve as a solid starting 
point for other Bambu printers - just expect to tweak temperatures and retraction 
slightly to match your machine.

---

## Background
I've always struggled maintaining filament profiles across brands and colors — 
this repo is where I'm parking mine so they don't get lost.

---

## Finding your profiles on disk
Bambu Studio stores filament profiles as plain JSON files you can copy directly 
into this repo. Find them here:

**Windows:**
`C:\Users\<you>\AppData\Roaming\BambuStudio\user\<user_id>\filament\`

**Mac:**
`~/Library/Application\ Support/BambuStudio/user/<user_id>/filament/`

Only commit the `.json` files - ignore any `.info` files Bambu Studio generates 
alongside them, those are local cache and not needed.

---

## Importing a profile
Drop the `.json` file into the same filament directory above, restart Bambu 
Studio, and the profile will appear in your filament list.

---

## Calibration
All current Bambu Lab printers support Flow Dynamics Calibration (Bambu's 
term for pressure advance / K factor). It's highly recommended to run this 
for each filament profile before printing - it significantly reduces corner 
blobs and stringing.

---

## Usage
Always run a test print before committing to a full print. Temperatures will 
vary by color — lower-pigment colors (white, natural, light grey) typically 
print 5°C cooler than darker or matte variants. Each profile notes what it 
was tuned for.

---

## Contributing
PRs welcome. If you have a profile for a machine or filament not covered here, 
open a PR or drop a comment.

---

## Contact
dominic@donavichsalami.com
