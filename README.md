# kawaba
https://go-kawaba.github.io/kawaba/index.html

## Creating Translations
### Single word:
```
<p>
  The quick brown <span class=tlt>{fox|cum}</span> jumped over the lazy dog
<p>
```
This example would create a paragraph where the translation for "fox" would be shown in the hovering box as "cum"

### Multiple words:
```
<p>
  <span class="tlt">
    {Hello|cum} {world!|cum!}
  </span>
<p>
```
This example would create a paragraph where the translation for "Hello world!" would be shown as two different words in seperate hovering boxes as "cum" and "cum!" respectively.
