# Welcome to ArchiveForJAM's External YouTube Subtitle Player!

This allows JO1's YouTube videos to be viewed with English subtitles, while counting the views directly to the original official video!

## Original Repository source

[http://github.com/siloor/youtube.external.subtitle](http://github.com/siloor/youtube.external.subtitle)

Please visit this link for the original repository and more details of its usage.

## Making subtitles

If you'd like to make subtitle for a video, there are a lot of tools helping you.

- YouTube has an automatic english speech recognition logic, that does a really good job and makes only a few mistakes. Its a very big help by timing the subtitles.
- On [DownSub.com](http://downsub.com/) you can download the subtitles from YouTube as an SRT file.
- There are a lot of good open source SRT editors out there.

## Limitations

By latest browsers, the embedded iframe requesting the fullscreen mode requires the whole window, so the script is not allowed to display anything in front of the player. That is why YouTube External Subtitle disables the fullscreen button by default. You can add your own fullscreen logic on your page, check the fullscreen example.

The script supports AMD.
