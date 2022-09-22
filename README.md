# theme-mariana

Fonts  
[IBM Plex Mono](https://github.com/IBM/plex)  
[Open Sans](https://www.opensans.com)  

Turn off font smoothing

```bash
defaults write com.apple.Terminal AppleFontSmoothing -int 0
defaults write com.sublimetext.4 AppleFontSmoothing -int 0
defaults write com.sublimemerge AppleFontSmoothing -int 0
defaults write com.apple.dt.Xcode AppleFontSmoothing -int 0
defaults write com.krill.CodeRunner AppleFontSmoothing -int 0
```

Turn on font smoothing

```bash
defaults delete com.apple.Terminal AppleFontSmoothing
defaults delete com.sublimetext.4 AppleFontSmoothing
defaults delete com.sublimemerge AppleFontSmoothing
defaults delete com.apple.dt.Xcode AppleFontSmoothing
defaults delete com.krill.CodeRunner AppleFontSmoothing
```

Sublime Text 4

copy to `~/Library/Application Support/Sublime Text/Packages`

<img align="center" src="https://github.com/chunqian/theme-mariana/blob/main/snapshot/sublime text.png">

Sublime Merge

Based on Theme Dark

copy to `~/Library/Application Support/Sublime Merge`

<img align="center" src="https://github.com/chunqian/theme-mariana/blob/main/snapshot/sublime merge.png">

Docsify

add `<link rel="stylesheet" href="mariana.css">` to index.html

<img align="center" src="https://github.com/chunqian/theme-mariana/blob/main/snapshot/docsify.png">

Terminal

<img align="center" src="https://github.com/chunqian/theme-mariana/blob/main/snapshot/apple terminal.png">

Xcode

copy to `~/Library/Developer/Xcode/UserData`

<img align="center" src="https://github.com/chunqian/theme-mariana/blob/main/snapshot/xcode.png">

CodeRunner

support 4.1 or newer

<img align="center" src="https://github.com/chunqian/theme-mariana/blob/main/snapshot/coderunner.png">

TODO
