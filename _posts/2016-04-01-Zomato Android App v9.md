---
layout: post
title: "Zomato Android App v9"
date:   2016-04-27
categories: [Zomato]
comments: true
image:
  feature: /v9.jpg
---

This version saw a major shift in how we handled our network and data. The underlying layers - network, transport and data were revisited for the first time since 2012, benchmarked against the industry standards and overhauled. <br>

<!--more-->

We moved from parsing data using archaic XML parsers to the new age GSON parsers, changed our HTTP client to OkHttp3 for an array of improvements.
You can read more about this change on <a href="https://engineering.zomato.com/rewriting-the-network-connection-layer-in-our-android-apps-11771c71012#.q88rc7v0k">Zomato's Engineering blog. </a>


<br>
<h5> Major changes in this version also included the following- </h5>
* <b>Bottom Navigation on the Home page</b> - We completely redessigned the Home Page to have mutiple fragments and placed a navigational tab at the bottom. These new tabs led to easier navigational UX.
* Introduced <b>Table Reservations through the app</b> -  We started a new vertical of operations to get into online table reservations.
* Integrated our inhouse <b>Data Analysing Engine (Jumbo!)</b> deep into the app - Moving past GA (Google Analytics), we integrated our inhouse data tool to give insights into user lifecycle & behavior, trends and feature usage. Events and screens were logged and batched light-weight API calls made near real-time monitoring possible.
* <b>Google App Indexing</b> - Read about App Indexing on the official <a href="https://developer.android.com/training/app-indexing/index.html">Android Developer's</a> page.
* <b>Requesting Permissions at Runtime</b> - Reworkd all the permissions in the app and started to ask for permission at run time instead of install time. Read more about them on the <a href="https://developer.android.com/training/permissions/requesting.html"> Android Developer's</a> page.
<br>
<br>

<h5> Here are some screens from this version- </h5>


*New Home Page with a Bottom Navigation Bar*
<img src="{{site.url}}/img/v9/v9_home.jpg">
<br>
<br>

*Runtime permissions* <br>
<img src="{{site.url}}/img/v9/v9_permissions.jpg" height="600" width="600">
<br>
<br>

*User page with detailed 'Dineline'* <br>
<img src="{{site.url}}/img/v9/v9_user_dineline.jpg"  height="1000" width="800">
