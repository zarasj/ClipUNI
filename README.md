# ClipUNI

ClipUNI is a Windows app that turns public YouTube videos, completed stream replays and local gameplay recordings into captioned vertical clips.

**[Download ClipUNI for Windows](https://github.com/zarasj/ClipUNI/releases/latest/download/ClipUNI.exe)**

Open ClipUNI, paste a link, choose a clip count and click **Create clips**. A channel link selects its latest completed upload. Use **Open clips folder** to reach your recordings and **Open finished clips** to see the latest batch.

The Windows download includes Python, the video tools and the Whisper small caption model. Transcription runs locally. YouTube downloads need internet access.

## Updates

ClipUNI checks this repository for new releases when it opens. Use **Check for updates**, **Download update** and **Restart to update**. Updates download changed files and reuse the installed tools and caption model. Restart waits while a clip batch is processing.

Release signatures and file checks protect the update download. ClipUNI keeps the previous version available if the updated app cannot open.

## Source and credits

**[Download the editable source](https://github.com/zarasj/ClipUNI/releases/latest/download/ClipUNI-source.zip)** includes the app, tests, build tools and instructions for publishing signed updates.

ClipUNI is a personal edition of [gouthamk16/clipper](https://github.com/gouthamk16/clipper). The original MIT license and author credit are retained. Bundled tools and models include their own license notices.

Automatic highlight choices and speech recognition can need review, especially when the main action happens quietly.
