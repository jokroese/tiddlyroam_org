---
title: Home
layout: default
---

{% include navbar.html %}

<div id="top"></div>

<div class="wrapper">
<div class="header">
<div class="container header-container">
<div class="col-lg-8 header-img-section">
<img src="{{ "assets/images/showcase.png" | relative_url }}">
</div>
<div class="col-lg-4 offset-lg-1 header-title-section">
<p class="header-subtitle">Wiki, meet notebook</p>
<h1 class="header-title">Your open source external brain</h1>
<p class="header-title-text"><b>tiddlyroam</b> is a notetaking app that let's you focus on your ideas. It'll join them up for you.</p>
<div class="learn-more-btn-section">
<a class="nav-link learn-more-btn" href="#about">Learn More</a>
</div>
</div>
</div>
</div>

<div class="strategy-section">
<div class="strategy-section-bg-graphics-section">
<img src="assets/images/network-side-image.png">
</div>
<div class="container strategy-container">
{% for benefit in site.data.benefits %}
<div class="col-lg-4 col-md-6 col-xs-8 offset-xs-2 strategy-card-section">
<div class="strategy-card">
<div class="strategy-card-icon-section">
<img src="assets/images/{{ benefit.image }}">
</div>
<h2>{{ benefit.title }}</h2>
<p>{{ benefit.description }}</p>
</div>
</div>
{% endfor %}
</div>
</div>

<div id="about"></div>

<div class="contact-section">
<div class="container contact-container">
<div class="col-md-6 contact-title-section">
<p class="contact-subtitle">What tiddlyroam does</p>
<h2 class="contact-title">Quickly create your own personal wiki</h2>
<p class="contact-text">
Add fragments of thoughts and findings whenever they come to you. TiddlyRoam will link them and help you spot the patterns.</p>
<div class="learn-more-btn-section">
<a class="nav-link learn-more-btn btn-invert" href="#quickstart">Get started</a>
</div>
</div>
<div class="col-md-6 contact-header-img">
<img src="assets/images/bookcase.png">
</div>
</div>
</div>

<div id="features"></div>

<div class="contact-section">
<div class="container contact-container">
<div class="col-md-6 contact-header-img">
<img src="assets/images/network.png">
</div>
<div class="col-md-6 contact-title-section">
<p class="contact-subtitle">What makes tiddlyroam tick</p>
<h2 class="contact-title">Bi-directional links</h2>
<p class="contact-text">
Bi-directional links allow you to see not just all the pages that a page links to, but also all pages that link to <i>it</i>.

</p>
<h2 class="contact-title">+ Graph maps</h2>
<p class="contact-text">
Graph maps visualise all the pages you have made and how they link together.</p>
<h2 class="contact-title">= Networked thought</h2>
<p class="contact-text">
The combination leads to what Roam calls ‘networked thought’. This is best explained by a tiddlyroam user:</p>
<h3 class="quote">"it's like having a second brain."</h3>
</div>
</div>
</div>

<div id="quickstart"></div>

<div class="services-sales-section">
<div class="container services-container">

<div class="col-lg-5 offset-lg-1 services-title-section">
<p class="services-subtitle">Zero to tiddlyroam hero</p>
<h2 class="services-title">Quickstart</h2>
<p class="services-text">
<ol>
<li>Download <a href = "https://github.com/joekroese/tiddlyroam/releases/download/v1.0/tiddlyroam.html">tiddlyroam.html</a></li>
<li>Download <a href = "https://github.com/Jermolene/TiddlyDesktop/releases">TiddlyDesktop</a></li>
<li>Open tiddlyroam.html in TiddlyDesktop</li>
</ol>
<p><b>Yes, it is that easy.</b></p>
</p>
<div class="learn-more-btn-section">
<a class="nav-link learn-more-btn" href="#tutorials">Next steps</a>
</div>
</div>
<div class="col-lg-6 services-header-img-section padding-0">
<img src="assets/images/quickstart.png">
</div>
</div>
</div>

<!-- <div id="clients"></div>
<div class="clients-section">
<div class="container clients-container">
<div class="clients-title-section">
<p class="clients-subtitle">All sorts of good folk use <b>tiddlyroam</b></p>
<h2 class="clients-title">User Showcase</h2>
</div>
<div class="clients-slider">
<div class="owl-carousel owl-theme clients-slider-section">
{% for user in site.data.users %}
<div class="item client-logo-section">
<img src="assets/images/{{ user.image }}">
</div>
{% endfor %}
</div>
</div>
</div>
</div> -->

<div id="tutorials"></div>

<div class="blog-section">
<div class="blog-section-right-bg">
<img src="assets/images/blog-section-right-bg.png">
</div>
<div class="blog-section-left-bg">
<img src="assets/images/blog-section-left-bg.png">
</div>
<div class="container blog-container">
<div class="blog-title-section">
<p class="blog-subtitle">Level up your external brain</p>
<h2 class="blog-title">Featured tutorials</h2>
</div>
<div class="blog-posts-section">
<div class="col-lg-4 col-md-8 col-xs-10 blog-post-card-container">
<div class="blog-post-card">
<div class="blog-post-icon">
<img src="assets/images/blog-card-1.png">
</div>
<h3 class="blog-post-title">For TiddlyWiki users</h3>
<p class="blog-post-subtitle">Transitioning to tiddlyroam with the plugin</p>
<a class="blog-post-link" href="#tiddlywiki-to-tiddlyroam">Read More</a>
</div>
</div>
<div class="col-lg-4 col-md-8 col-xs-10 blog-post-card-container">
<div class="blog-post-card">
<div class="blog-post-icon mb-4">
<img src="assets/images/blog-card-2.png">
</div>
<h3 class="blog-post-title">Quickstart</h3>
<h4 class="blog-post-subtitle">Write notes in tiddlyroam in less than two minutes.</h4>
<!-- <p class="blog-post-text mb-4">The tiddlyroam approach is built on simplicity.</p> -->
<a class="nav-link learn-more-btn" href="#quickstart">Read More</a>
</div>
</div>
<div class="col-lg-4 col-md-8 col-xs-10 blog-post-card-container">
<div class="blog-post-card">
<div class="blog-post-icon">
<img src="assets/images/head-repair.png">
</div>
<h3 class="blog-post-title">Extending tiddlyroam</h3>
<p class="blog-post-subtitle">Got the basics? Set up tiddlyroam on mobile.</p>
<a class="blog-post-link" href="#extending-tiddlyroam">Read More</a>
</div>
</div>
</div>
</div>
</div>

<div id="community"></div>

<div class="contact-section">
<div class="container contact-container">
<div class="col-md-6 contact-title-section">
<p class="contact-subtitle">Community</p>
<h2 class="contact-title">tiddlyroam:<br>built by people like you and me.</h2>
<p class="contact-text"><b>tiddlyroam</b> is an open source project. Our community supports new users, request new features and fix any cracks.</p>
<div class="learn-more-btn-section">
<a class="nav-link learn-more-btn" href="https://github.com/joekroese/tiddlyroam">Meet the community</a>
</div>
</div>
<div class="col-md-6 contact-header-img">
<img src="assets/images/contact-header-img.png">
</div>
</div>
</div>

{% include footer.html %}

{% include footer_scripts.html %}