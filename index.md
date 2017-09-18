---
layout: default
title: Praqma Mail Signature
author: Lars Kruse
organization: Praqma
repo: photogallery
---

This will generate images in Json format for the carousel
{: .cuff}

## Fill out Userid and Albumid:

<script type="text/javascript" src="http://code.praqma.com/javascripts/jquery-1.11.1.js"></script>

<form action="./create.html">
  <div style="width: 140px;display: block;float: left;">Userid:</div>
  <input id="user-id" type="text" name="user" style="width:250px;">
<br>
  <div style="width: 140px;display: block;float: left;">Albumid:</div>
  <input id="album-id" type="text" name="album" style="width:250px;">
  <br>
  <div>&nbsp;</div>
  <div style="width: 140px;display: block;float: left;">&nbsp;</div><input type="submit" value="Submit">
</form>

## What do I do?

* Fill out both field and the press submit, this will redirect you to a page with JSON copy the data into a file with a name of you choice. remember it must end with the file-extension `.json` Example `something.json`
* Save the file you just created into the folder called `_json-images` in code-conf
