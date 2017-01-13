---
title: Etch-Your-Sketch
layout: default
modal-id: 7
date: 2017-01-13
small-img: etch-your-sketch.png
big-img: etch-your-sketch.png
alt: Etch-Your-Sketch
tools: Java, Android SDK, Canvas & SurfaceView

---

Inspired by the classic analog etching toy, this app lets you use two knobs to sketch anything you can imagine. 

<div class="center-links">
    <a href='https://play.google.com/store/apps/details?id=com.charlesdrews.etchyoursketch' target="_blank">
        <img class="play-store-app-badge" alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/apps/en-play-badge.png' />
    </a>
    <a class="btn btn-md btn-outline github-project-link" href="https://github.com/charlesdrews/etch-your-sketch" target="_blank">
        <i class="fa fa-github"></i>
        <span class="small">View on GitHub</span>
    </a>
</div>

This app was a good opportunity to implement some custom Android views for the knobs/dials, use the accelerometer to detect shaking, and use FileProvider to share content to other apps. The user's etchings are rendered to the screen using Android's Canvas and SurfaceView APIs.

Features include:

  - Change colors & line widths
  - Precision erasing - or shake your phone to erase the whole thing (of course!)
  - Save your etchings to your gallery
  - Share your etchings to social media, messaging apps, etc.
