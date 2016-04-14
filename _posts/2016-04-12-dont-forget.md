---
title: Don't Forget
layout: default
modal-id: 0
date: 2016-04-14
img: dont-forget.png
alt: Don't Forget
tools: Java, Android SDK, APIs/JSON (Retrofit), NoSQL (Realm)

---

<div style="text-align:center">
    <a href='https://play.google.com/store/apps/details?id=com.charlesdrews.dontforget&utm_source=global_co&utm_medium=prtnr&utm_content=Mar2515&utm_campaign=PartBadge&pcampaignid=MKT-Other-global-all-co-prtnr-ap-PartBadge-Mar2515-1' target="_blank">
        <img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/apps/en-play-badge.png' width="180"/>
    </a>
</div>

Don't Forget is an app that delivers weather, task, and birthday reminders
to users via notifications custom-timed to fit their schedule.
The app is very customizable thanks to a robust set of user-controlled
preferences on the settings screen. Check out the source code on
[GitHub](https://github.com/charlesdrews/Dont-Forget){:target="_blank"}.

This project was a great opportunity to use some popular third-party
libraries like [Retrofit](http://square.github.io/retrofit/){:target="_blank"},
[Picasso](http://square.github.io/picasso/){:target="_blank"}, and
[Realm](https://realm.io/){:target="_blank"}.
It was also a good exercise in multithreaded, asynchronous programming,
using a *Sync Adapter* to gather data from the
[Weather Underground API](http://www.wunderground.com/weather/api/){:target="_blank"}
and *Intent Services* to schedule and launch notifications.