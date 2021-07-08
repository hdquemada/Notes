# YouTube-dl Command to see all formats:

youtube-dl -F [or --list-formats] (URL)

# Then repeat:

youtube-dl -f (the number from the list you want) (URL)

# To automatically download the best format:

youtube-dl -f best (URL)

# To extract audio only:

--extract-audio --audio-format mp3 video-url

# To extract playlist to mp3

youtube-dl --extract-audio --audio-format mp3 -o "%(title)s.%(ext)s" <url to playlist>
