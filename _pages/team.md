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

/* hover image (starts hidden) */
.photo-hover-img {
  position: absolute;
  top: 0;
  left: 0;
  opacity: 0;
  transition: opacity 0.25s ease-in-out;
}

/* crossfade on hover */
.photo-hover:hover .photo-hover-img {
  opacity: 1;
}

.photo-hover:hover .photo-main {
  opacity: 0;
}

/* --- Lab alumni table --- */
.alumni-table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 1em;
}

.alumni-table th,
.alumni-table td {
  text-align: left;
  padding: 0.65em 1em 0.65em 0;
  vertical-align: top;
}

.alumni-table th {
  border-bottom: 2px solid #ddd;
}

.alumni-table td {
  border-bottom: 1px solid #eee;
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
    Carver College of Medicine<br/>
    University of Iowa
  </div>
</div>

<!-- DOUGLAS -->
<div class="person">
  <div class="photo-hover">
    <img class="photo-main" src="../files/douglas1.jpeg" alt="Douglas Dos Santos, PhD">
    <img class="photo-hover-img" src="../files/douglas2.jpeg" alt="Douglas Dos Santos, PhD (hover)">
  </div>
  <div>
    <strong>Douglas Dos Santos, PhD</strong><br/>
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

<!-- ABBY -->
<div class="person">
  <img src="../files/Abby_McLeod.jpeg" alt="Abby McLeod" style="width:40%; max-width:360px; border-radius:8px;">
  <div>
    <strong>Abby McLeod</strong><br/>
    <em>Lab Manager</em>
  </div>
</div>

<!-- JOCELYN -->
<div class="person">
  <div class="photo-hover">
    <img class="photo-main" src="../files/JR_headshot.jpeg" alt="Jocelyn Riley">
    <img class="photo-hover-img" src="../files/JR_funpic.jpeg" alt="Jocelyn Riley (hover)">
  </div>
  <div>
    <strong>Jocelyn Riley</strong><br/>
    <em>Graduate Student</em>
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
    <em>Graduate Student</em>
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

<br/>

## Lab Alumni

<table class="alumni-table">
  <thead>
    <tr>
      <th>Name</th>
      <th>Current Position</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Weihong Zhou</strong> (2025–2026)</td>
      <td>Retired</td>
    </tr>
  </tbody>
</table>