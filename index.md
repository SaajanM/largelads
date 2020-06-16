---
title: Large Lads Inc.
description: Join The Union!
videos:
  - url: https://www.youtube.com/watch?v=TrXSV1LzAdc
    thumbnail: https://img.youtube.com/vi/TrXSV1LzAdc/hqdefault.jpg
  - url: https://www.youtube.com/watch?v=T7gVHBJWHPY
    thumbnail: https://img.youtube.com/vi/T7gVHBJWHPY/hqdefault.jpg
  - url: https://www.youtube.com/watch?v=VJjBQUr5PEo
    thumbnail: https://img.youtube.com/vi/VJjBQUr5PEo/hqdefault.jpg
---
## About

Large Lads Inc. is a professional group of friends who host a Youtube channel and a Minecraft server.

Our goal is to provide QUALITY content for all to watch and enjoy. And as always, don't forget to join the union!

### Youtube
In order to access our fresh off the press, piping hot, quality visual content please visit our youtube channel [here](https://www.youtube.com/channel/UCkBDQMLJEPbitLc2z1BWf-A) or view some of our top videos below.

<div class="video-slider" style="display: block; width:100%;height:fit-content;background-image:linear-gradient(120deg, #155799, #159957);">
    {% for video in page.videos %}
    <div class="video" style="display: inline-block;width: fit-content;height: min-content;padding:1.75rem 0rem;">
        <a href={{ video.url }}><img src={{ video.thumbnail }} style="height:8rem; width:auto;"></a>
    </div>
    {% endfor %}
</div>

### Minecraft

While you can't directly join our Minecraft server due to our stringent whitelisting policies, feel free to subscribe to our Youtube channel to watch the latest and greatest of Large Lads Inc's Minecraft adventure.
