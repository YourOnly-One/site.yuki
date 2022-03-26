+++
title = "再生中"
date = "2020-03-25T07:00:00+00:00"
lastmod = "2020-03-25T07:00:00+00:00"
weight = "40"
+++

<!--
  Developed by Prashant Shrestha
  + https://prashant.me
-->
<!--
  * Modified by ᜌᜓᜃᜒ (Yuki ・ 雪亮) 🇵🇭
  *   - https://YourOnly.One
  *
  * 2021-01-31:
  *   - Added trackalbum
  *   - Moved emoji outside of js file into HTML area
  * 2021-01-30: Switched to Emoji instead of icon files
--->
<link rel="stylesheet" property="stylesheet" href="https://rsc.youronly.one/css/LastFM-NowPlaying.min.css" />
<script src="https://rsc.youronly.one/js/LastFM-NowPlaying.min.js" defer="defer"></script>
<div class="nowplayingcard">
  <div class="nowplayingcontainer-inner">
    <img id="trackart" src="#">
    <div class="trackInfo">
      <span class='emoji'>🎧</span><a id="tracktitle"></a><br/>
      <span class='emoji'>📀</span><a id="trackalbum"></a><br/>
      <span class='emoji'>🎤</span><a id="trackartist"></a>
    </div>
  </div>
</div>
