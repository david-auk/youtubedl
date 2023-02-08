# Use:
### Download youtube audio/video's w/ extra features (optimised for audio)

---

**youtubedl -u "YouTube-url" [options]**

\[Automaticly sync music to iPhone (**youtubedl -i**)]

\[Extracting extra metadata, eg. release year, artist, title and lyrics (if the video has captions)]

<dl>
  <dt>Thumbnail (als works with other image input sources)</dt>
  <dd>Generate thumbnail using the metadata & the thumbnail of the target video</dd>
  <dd>Use <strong>-E</strong> for extra options</dd>
  <dd>Use <strong>-m "Artist - Title"</strong> to overwrite the original metadata, handy for <strong>-T</strong></dd>
  <dd>(<strong>youtubedl -au</strong> URL <strong>-T</strong> [image input, optional])</dd>
  <dt>Audio slicing (audio only)</dt>
  <dd>From startpoint (<strong>youtubedl -au</strong> URL <strong>-s</strong> STARTPOINT)</dd>
  <dd>From endpoint (<strong>youtubedl -au</strong> URL <strong>-e</strong> ENDPOINT)]</dd>
  <dd>(you can also use <strong>-s c</strong> to automatically slice all the silence out)]</dd>
</dl>

# youtubedl-installation (macOS)
Download from gitpage: **git clone https://github.com/david-auk/youtubedl ~/.github; chmod 755 ~/.github/youtubedl.sh; cd ~/.github**

Run the script via: **./youtubedl.sh**

