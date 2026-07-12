# One Piece TCG — update feed
The app checks version.json here and downloads update.zip.
Publish updates: bump package.json version in the game, run `node tools/make-update.js`,
copy dist-update/* here, commit, push.
