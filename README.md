# SimGolf HD Art Pack

All of the original art from Sid Meier's SimGolf (2002) upscaled 4x for the **SimGolf Mod**: golfers, buildings, trees, ground, animals, menus and effects. With it on, the game looks sharp and smooth at 1080p, 1440p and 4K instead of blocky.

This pack only works with the SimGolf Mod. It does not change the original game on its own.

## Install

The SimGolf Mod's setup downloads and installs this pack for you when you pick **HD art**. You only need the steps below if you want to install it by hand.

1. Close the game.
2. Open the **Releases** page on the right and download every `simgolf-hd-art-partNN.zip` file of the latest release, plus `SHA256SUMS.txt`.
3. Make a folder called `art\upscaled` inside your SimGolf Mod folder (the folder that has `golf.exe`).
4. Extract every part into that same `art\upscaled` folder. All parts go into the same place; the order does not matter. When it is done, `art\upscaled\manifest.jsonl` and `art\upscaled\index.tsv` should be there.
5. Open `golf.ini` in the SimGolf Mod folder and set:

   ```ini
   art=upscaled
   art_dir=art/upscaled
   ```

6. Start the game. In **Options > Graphics > Textures** you can switch between HD, Pixel HD and Original at any time.

## What is in it

- 132,407 images upscaled 4x with Real-ESRGAN, matched to the game's own sprite sheets frame by frame.
- `manifest.jsonl` lists every image with its source file, category and size.
- Split into parts under 2 GB each because of GitHub's file size limit.

## Credits and legal

Unofficial fan project, not affiliated with or endorsed by Firaxis Games, Electronic Arts or Take-Two Interactive. SimGolf and its art are their property; this pack is an upscale of that art and is shared with permission. It will be taken down on request from the rights holder.

## Support

Free hobby project. If you enjoy it, you can [buy me a coffee on Ko-fi](https://ko-fi.com/finalpantasy). Thank you!
