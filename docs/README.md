# docsify-wikilink

<p align="center">
  <img src="https://docsify.js.org/_media/icon.svg" />
  <br />
  <code>docsify-wikilink</code>
</p>

[![jsdelivr](https://data.jsdelivr.com/v1/package/npm/docsify-wikilink/badge)](https://www.jsdelivr.com/package/npm/docsify-wikilink)

This is a plugin allow wikilinks features for markdown files of docsify.

## usage
add this line of code to Docsify project to install this plugin.
```html
<script src="https://cdn.jsdelivr.net/npm/docsify-wikilink@1"></script>
```
## example

> use of wikilink.

link 2 a file name 'fileName.md' in the same directory.

### direct link

```
[[fileName]]
```
[[fileName]]

### link with alias

```
[[fileName|Show Link]]  
```
[[fileName|Show Link]]  

### link with topic

```
[[fileName#topic2]]
```
[[fileName#topic2]]

### link with topic and alias

```
[[fileName#topic2| topic2 of FileName]]
```
[[fileName#topic2| topic2 of FileName]]

### link to subPath
```
[[subPath/subPathFile]]
```
[[subPath/subPathFile]]