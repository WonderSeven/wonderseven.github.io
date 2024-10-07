---
show: true
width: 4
date: 2020-01-12 00:01:00 +0800
---
<div>
  <img data-src="{{ 'assets/images/covers/cover1.jpg' | relative_url }}" class="lazy w-100 rounded-sm" src="{{ '/assets/images/empty_300x200.png' | relative_url }}">

  <div class="card-img-overlay" style="overflow: scroll; background: rgb(255,255,255,0.8)">
   <h3 class="card-title">我的小站</h3>
   <h5 class="card-text">
   <a href="{{ 'articles' | relative_url }}">
      随笔 读后感 游记 诗歌
    </a></h5>
    <p class="card-text">
      自从高二开始创作，到现在已经六年了，这六年的写作也是时断时续，主要是自己作为一个理科生（码农），周围的环境不允许，而且学业的压力很大也就没时间去发展自己的文学兴趣了，现今趁着自己的研究生涯还未彻底展开，正好有时间正好整理一下，好好和自己文学梦来个亲密约会QAQ。不得不说，看着自己以前写的东西，可能外人无法理解，但是自己当时创作时的感觉还是能够唤起，也许这就是文字的魅力吧。当然，我也会把写作作为一种习惯继续下去。

看着自己的作品，真是一股青春的气息扑面而来，即便以前的自己是脆弱的、敏感的，那也是我啊，不可割弃的我啊！所以即便有些作品格局略小，我也未进行改动，在作品中有对异性的渴望和踌躇，其实具体的目标是有的，但又不仅止于此，更多是对自己不可推测的未来的思考和迷茫。现在，自己更加享受青春、享受生活，在步向更好的自己的路上。不得不说，我的朋友真是帮助我很多，在这里也是感谢他们对我的宽容和无私奉献，遇见、是命运最好的注定。I love what I own now.
    </p>
    <p class="card-text">
      {% raw %}
      <code>&lt;img data-src=&quot;[Image URL]&quot; class=&quot;lazy w-100 rounded-sm&quot; src=&quot;{{ '/assets/images/empty_300x200.png' | relative_url }}&quot;&gt;</code>
      {% endraw %}
    </p>
  </div>
</div>
