## Description ##
SBBEditor is coded with javascript. It's developed for simplicity and for simple usage. You can use the Simple BBCode Editor to add your bbcode's to your textarea/inputbox/etc..

## Usage ##
First, you need to insert editor.js to your html file;

```
<script src="sbbeditor.js" type="text/javascript"></script>
```

After that you can give a function to your html elements (button, image, string etc..) like this;

```
<input type="button" name="bold" value="B" onclick="javascript:addtag('contentArea','bold');">
<input type="button" name="italic" value="I" onclick="javascript:addtag('contentArea','italic');">
<input type="button" name="uline" value="U" onclick="javascript:addtag('contentArea','underline');">
<input type="button" name="url" value="URL" onclick="javascript:addtag('contentArea','url');">
<input type="button" name="img" value="IMG" onclick="javascript:addtag('contentArea','img');">
<br/>
<textarea id="contentArea" rows="10" cols="60"></textarea>
```


