# build-ios
This is a tutorial repository for building a Godot Project IPA with GitHub actions. Check it out here: https://mak448a.github.io/blog/compile-ios-godot-without-mac
Please give this repo a star if it helps! :)

If you can't upload to GitHub successfully, you may need to upload the file to dropbox and download it. I haven't bothered to add it yet to this repo, but if you *really* need and are desperate, here's the snippet you need to integrate. Copy the link to your dropbox file. Replace YOURLINKHERE with it. MAKE SURE TO CHANGE `dl=0` in the URL to `dl=1`.
```
wget -O archive.zip "YOURLINKHERE"
unzip archive.zip -d .
```
