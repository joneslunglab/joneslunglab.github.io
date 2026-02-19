---
layout: single
permalink: /team/
author_profile: false
title: "Meet the Lab"
---

<style>
/* --- Team page layout --- */
.person {
  display: flex;
  align-items: center;
  gap: 1.5em;
  margin-bottom: 2.5em;
}

@media (max-width: 768px) {
  .person {
    flex-direction: column;
    align-items: flex-start;
  }
}

/* --- Hover swap photos (used only for people who have 2 images) --- */
.photo-hover {
  position: relative;
  width: 40%;
  max-width: 360px;
  overflow: hidden; /* optional but helps if the hover image is taller */
}

.photo-hover img {
  width: 100%;
  height: auto;
  border-radius: 8px;
  display: block;
}

/* main image (starts visible) */
.photo-main {
  opacity: 1;
  transition: opacity 0.25s ease-in-out;
}

/* hover image (starts hidden, vertically centered) */
.photo-hover-img {
  position: absolute;
  top: 50%;
  left: 0;
  width: 100%;
  transform: translateY(-50%);
  opacity: 0;
  transition: opacity 0.25s ease-in-out;
}

/* crossfade on hover: show hover image, hide main image */
.photo-hover:hover .photo-hover-img {
  opacity: 1;
}

.photo-hover:hover .photo-main {
  opacity: 0;
}
</style>


<br/>

<!-- DAKOTA -->
<div class="person">
  <div class="photo-hover">
    <img class="photo-main" src="../files/dakota photo.jpeg" alt="Dakota Jones, PhD">
    <img class="photo-hover-img" src="../files/dakota photo2.jpeg" alt="Dakota Jones, PhD (hover)">
  </div>
  <div>
    <strong>Dakota Jones, PhD</strong><br/>
    <em>Principal Investigator</em><br/><br/>
    Assistant Professor<br/>
    Department of Anatomy and Cell Biology<br/>
    Carver School of Medicine<br/>
    University of Iowa
  </div>
</div>

<!-- WEIHONG (NO HOVER) -->
<div class="person">
  <img src="../files/weihong.jpg" alt="Weihong Zhou" style="width:40%; max-width:360px; border-radius:8px;">
  <div>
    <strong>Weihong Zhou, PhD</strong><br/>
    <em>Lab Manager</em>
  </div>
</div>

<!-- YUN -->
<div class="person">
  <div class="photo-hover">
    <img class="photo-main" src="../files/yun.jpeg" alt="Yeo Gyun Yun">
    <img class="photo-hover-img" src="../files/yun2.jpeg" alt="Yeo Gyun Yun (hover)">
  </div>
  <div>
    <strong>Yeo Gyun Yun, PhD</strong><br/>
    <em>Postdoctoral Fellow</em>
  </div>
</div>

<!-- ELLYSE -->
<div class="person">
  <div class="photo-hover">
    <img class="photo-main" src="../files/ellyse.jpeg" alt="Ellyse Froehlich">
    <img class="photo-hover-img" src="../files/ellyse2.jpg" alt="Ellyse Froehlich (hover)">
  </div>
  <div>
    <strong>Ellyse Froehlich</strong><br/>
    <em>Postbac</em>
  </div>
</div>

<!-- BRUCE -->
<div class="person">
  <div class="photo-hover">
    <img class="photo-main" src="../files/bruce.JPG" alt="Bruce Warmann">
    <img class="photo-hover-img" src="../files/bruce2.jpg" alt="Bruce Warmann (hover)">
  </div>
  <div>
    <strong>Bruce Warmann</strong><br/>
    <em>Rotating Graduate Student</em>
  </div>
</div>
