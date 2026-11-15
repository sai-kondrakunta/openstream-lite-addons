# OpenStream Lite addons

`addons.json` is the addon list for OpenStream Lite. Each time the app starts it reads this file and installs any
address it hasn't been given before (switched on). Viewers can turn any addon off or remove it in
Settings > Addons; a removed addon is not added back unless its address is new to the list.

Format: `{ "addons": [ "https://.../manifest.json", ... ] }`. Edit the file on GitHub; apps pick it up on their next start.
