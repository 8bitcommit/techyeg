---
layout: single
title: "About Us"
permalink: /about/
---
<!--We’re TechYEG — Edmonton’s local tech handyman service. Think of us as your neighborhood Tech Squad without the big box store pricing.-->
Your on-call tech support for computers, networks, and smart devices—delivered locally in Edmonton.

<style>
  .services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    margin-top: 2rem;
    text-align: center;
  }
  .service-card img {
    width: 100%;
    height: 180px; /* consistent height */
    object-fit: cover; /* crop neatly */
    border-radius: 8px;
  }
  .service-card {
    padding: 1rem;
    border-radius: 12px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    background: #fff;
  }
</style>

<div class="services-grid">

  <div class="service-card">
    <img src="{{ '/assets/images/Tv-mount.jpg' | relative_url }}" alt="TV Mount">
    <p><strong>TV & Smarthome</strong><br>Seamless setup of smart TVs, security, and home automation.</p>
  </div>

  <div class="service-card">
    <img src="{{ '/assets/images/Network.jpg' | relative_url }}" alt="Network Setup">
    <p><strong>Wi-Fi & Networking</strong><br>Reliable connections for your home or office — no dead zones.</p>
  </div>

  <div class="service-card">
    <img src="{{ '/assets/images/Speakers.jpg' | relative_url }}" alt="Home Theatre Setup">
    <p><strong>Audio Visual</strong><br>Custom home theatre integration.</p>
  </div>
  <div class="service-card">
    <img src="{{ '/assets/images/secure.jpg' | relative_url }}" alt="security">
    <p><strong>Network Security Cameras</strong><br>Professional installation for reliable 24/7 coverage.</p>
  </div>

</div>