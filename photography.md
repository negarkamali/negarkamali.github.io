---
layout: photography
title: Photography
permalink: /photography/
---

## Photography

I photograph my family and friends, travels to Iran and other parts of the world, and scenes from daily life in Chicago.

<div class="masonry">
<div class="masonry-item"><img src="/images/photography/my-photos/Alcatraz.JPG" alt="Alcatraz" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Armenia 2017.JPG" alt="Armenia 2017" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Berkeley-1.JPG" alt="Berkeley" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Chicago  somewhere 2017 .JPG" alt="Chicago 2017" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Chicago 2016 .JPG" alt="Chicago 2016" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Chicago winter 2017.JPG" alt="Chicago winter 2017" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Chicago-2017-.JPG" alt="Chicago 2017" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Chicago-2017.JPG" alt="Chicago 2017" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Chicago-train-2017.JPG" alt="Chicago train 2017" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Chicago.JPG" alt="Chicago" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Coronado 2.JPG" alt="Coronado" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Coronado islan.JPG" alt="Coronado Island" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Holland michigan 2017 2.JPG" alt="Holland Michigan 2017" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Holland michigan 2017.JPG" alt="Holland Michigan 2017" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Iran-2017.JPG" alt="Iran 2017" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Iran-family trip.JPG" alt="Iran family trip" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Mesudim science and industry 2016.JPG" alt="Museum of Science and Industry 2016" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/My kinda downtown .JPG" alt="Downtown Chicago" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Nevada 2017.JPG" alt="Nevada 2017" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Sf-1.JPG" alt="San Francisco" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Sf-2.JPG" alt="San Francisco" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Sf-3.JPG" alt="San Francisco" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Sf-4.JPG" alt="San Francisco" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Sf-5.JPG" alt="San Francisco" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Tehran university 2017.JPG" alt="Tehran University 2017" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Uic-2017-fall.JPG" alt="UIC fall 2017" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Uic-2017.JPG" alt="UIC 2017" loading="lazy"></div>
<div class="masonry-item"><img src="/images/photography/my-photos/Uic.JPG" alt="UIC" loading="lazy"></div>
</div>

<div class="pagination">
  <span class="page-current">1</span>
  <a href="/photography/2/">2</a>
</div>

<!-- Lightbox overlay -->
<div id="lightbox" onclick="this.style.display='none'">
  <img id="lightbox-img" src="" alt="">
</div>

<style>
.masonry {
  columns: 3;
  column-gap: 4px;
  margin-top: 16px;
}
.masonry-item {
  break-inside: avoid;
  margin-bottom: 4px;
  cursor: pointer;
  overflow: hidden;
}
.masonry-item img {
  width: 100%;
  display: block;
  transition: opacity 0.3s;
}
.masonry-item:hover img {
  opacity: 0.8;
}
#lightbox {
  display: none;
  position: fixed;
  top: 0; left: 0;
  width: 100vw;
  height: 100vh;
  background: rgba(0, 0, 0, 0.95);
  z-index: 9999;
  cursor: pointer;
  justify-content: center;
  align-items: center;
}
#lightbox img {
  max-width: 90vw;
  max-height: 90vh;
  object-fit: contain;
}
.pagination {
  display: flex;
  justify-content: center;
  gap: 12px;
  margin-top: 32px;
  padding-bottom: 40px;
  font-size: 16px;
}
.pagination a {
  color: #777;
  text-decoration: none;
  padding: 6px 12px;
  border: 1px solid #333;
  border-radius: 4px;
}
.pagination a:hover { color: #fff; border-color: #666; }
.page-current {
  color: #fff;
  padding: 6px 12px;
  border: 1px solid #fff;
  border-radius: 4px;
}
@media (max-width: 800px) {
  .masonry { columns: 2; }
}
@media (max-width: 500px) {
  .masonry { columns: 1; }
}
</style>

<script>
document.querySelectorAll('.masonry-item img').forEach(function(img) {
  img.addEventListener('click', function() {
    var lb = document.getElementById('lightbox');
    document.getElementById('lightbox-img').src = this.src;
    lb.style.display = 'flex';
  });
});
</script>
