# Assets to create for paste-vault

## logo.png вЂ” 256x256, transparent, dark theme
📋 Neon shield/gear motif matching $paste-vault$ brand color. See master prompt in _shared docs.

## banner.png вЂ” 1280x640, background #0d1117
Large bold title $paste-vault$, subtitle gray #8b949e, thin gradient line #00ff9dв†’#bc8cff.

## screenshots/main.png вЂ” 1280x800
History popup — searchable list with previews and pinned section

## screenshots/settings.png вЂ” 1280x800
Settings — exclusions, encryption toggle, hotkeys

## screenshots/results.png вЂ” 1280x800
Snippet editor — rich text with tags and folders

## gifs/demo.gif вЂ” 800x500, 8s, 12fps, <8MB
1. Open app, 2. click main action, 3. status turns green, 4. toggle a feature, 5. return.
ffmpeg: -vf "fps=12,scale=800:-1:flags=lanczos,split[s0][s1];[s0]palettegen[p];[s1][p]paletteuse"