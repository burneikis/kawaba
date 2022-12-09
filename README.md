# kawaba
https://go-kawaba.github.io/kawaba/index.html

This is where the project is now, I have some old commits in the repo and it is a fork of my original project that the team (for some reason idfk) un-forked manually.
https://github.com/GJ-u/kawaba

## Creating Translations
### Single word:
```
<p>
  The quick brown <span class=tlt>{fox|xof}</span> jumped over the lazy dog
<p>
```
This example would create a paragraph where the translation for "fox" would be shown in the hovering box as "xof"

### Multiple words:
```
<p>
  <span class="tlt">
    {Hello|olleh} {world!|dlrow}!
  </span>
<p>
```
This example would create a paragraph where the translation for "Hello world!" would be shown as two different words in seperate hovering boxes as "olleh" and "dlrow" respectively.
