![](https://cdn.statically.io/img/bread.shx.gg/f=auto,w=450,h=450/Bb9YgJ.png)

# youtube-box

# DEPRECATED

**Update Every 8 mins**

[Original git](https://github.com/extremecodetv/youtube-box)

# How to use
1. Create a new public GitHub Gist (https://gist.github.com/), create files named `Last Video On Youtube.md`

2. Create an access token with the gist scope and copy it. (https://github.com/settings/tokens/new)

3. Get a YouTube API key - follow these [steps](https://developers.google.com/youtube/v3/getting-started) note that you don't need an Oauth scope for this.

4. [Click me and make repo](https://github.com/keepsobp/youtube-box/generate)

5. Edit the environment variables in `.github/workflows/main.yml`:

   - **CHANNEL_ID**: The ID portion of your YouTube channel url: `https://www.youtube.com/channel/`**`UCl7UlXHLVg2hs7VbrZs0y3Q`**

   - **GIST_ID**: The ID portion of your gist url: `https://gist.github.com/KeepSOBP/`**`a1b1dd01baa4f1342b05fbde5f80f782`**

6. Go to the repo `Settings` > `Secrets`

7. Add the following environment variables:

   - **GH**: The GitHub access token generated above.
   - **YAK**: The YouTube API key generated above.

8. Click `actions` tab and enable actions if disable

# owo thanks
<!-- start: ytbox -->
<!-- end: ytbox -->


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FKeepSOBP%2Fyoutube-box.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FKeepSOBP%2Fyoutube-box?ref=badge_large)
