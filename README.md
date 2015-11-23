# Syosetu-Downloader
Download chapters from Syosetsu ni Narou — forked from LordZero25.

**Differences from the original:**
- Support non-Windows environment, Linux + Mono framework to be specific. The original will create very "funny" outputs if it's not Windows.
- GUI tweaks to be a bit more user-friendly. Tooltips + "In Progress..." indicator.
- Support CLI-only usage (for batch, automation, and CLI freaks). 
- Verbose CLI status.
- Target .Net version 2.0 instead of 4.0. Just because I use an older version of Visual Studio.

**CLI usage:**
- Syntax: `syosetuDownloader.exe <link> [<start> [<end>]]`
- Example 1 (grab chapter 88 - 99): `syosetuDownloader.exe 'http://ncode.syosetu.com/n7505bx/' 88 99`
- Example 2 (grab chapter 88 - end): `syosetuDownloader.exe 'http://ncode.syosetu.com/n7505bx/' 88`
- Example 3 (grab all chapters): `syosetuDownloader.exe 'http://ncode.syosetu.com/n7505bx/'`
- Note: It will start in normal GUI mode if no paramenter is provided.

**Features (original):**
- Support links with the pattern "http://*.syosetu.com/xxxxxxx"
- Downloaded chapters are on .exe folder/[novel name]/Chapter [num] - [chapter name].txt ([num]=incrementing number | [novel name] and [chapter name] are on japanese)
- Option to specify a chapter range i.e. if you want to only download say chapters 3-10
- This will download everything until it reaches an error page

**Notes (original):**
- If no chapter range is specified it will download everything
- If "from" is blank it will start from chapter 1
- If "to" is blank it will end on the latest/last chapter
- No volume support
- No loading screen whatsoever (sorry for that)
- "chapter 1" is "http://*.syosetu.com/xxxxxxx/1"
- Replaces illegal characters on filename with "□"

**[Releases Here](https://github.com/dreamer2908/Syosetu-Downloader/releases/)**
