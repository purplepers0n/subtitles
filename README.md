# Welcome to ArchiveForJAM's External YouTube Subtitle Player!

This allows JO1's YouTube videos to be viewed with English subtitles, while counting the views directly to the original official video!

## GITHUB

[http://github.com/siloor/youtube.external.subtitle](http://github.com/siloor/youtube.external.subtitle)

Please, don't forget to star the repository if you like (and use) the script. This will let me know how many users it has and then how to proceed with further development.

## Making subtitles

If you'd like to make subtitle for a video, there are a lot of tools helping you.

- YouTube has an automatic english speech recognition logic, that does a really good job and makes only a few mistakes. Its a very big help by timing the subtitles.
- On [DownSub.com](http://downsub.com/) you can download the subtitles from YouTube as an SRT file.
- There are a lot of good open source SRT editors out there.

## Examples

- [Basic example](http://siloor.github.io/youtube.external.subtitle/examples/basic/)
- [Load an SRT file](http://siloor.github.io/youtube.external.subtitle/examples/srt/)
- [More subtitles](http://siloor.github.io/youtube.external.subtitle/examples/moresubtitles/)
- [More SRT subtitles](http://siloor.github.io/youtube.external.subtitle/examples/moresrtsubtitles/)
- [More SRT subtitles by more videos](http://siloor.github.io/youtube.external.subtitle/examples/moresrtsubtitlesmorevideos/)
- [Style subtitles](http://siloor.github.io/youtube.external.subtitle/examples/style/)
- [Fullscreen](http://siloor.github.io/youtube.external.subtitle/examples/fullscreen/)
- [Responsive](http://siloor.github.io/youtube.external.subtitle/examples/responsive/)
- [Custom render method](http://siloor.github.io/youtube.external.subtitle/examples/customrendermethod/)

## Limitations

By latest browsers, the embedded iframe requesting the fullscreen mode requires the whole window, so the script is not allowed to display anything in front of the player. That is why YouTube External Subtitle disables the fullscreen button by default. You can add your own fullscreen logic on your page, check the fullscreen example.

The script supports AMD.
