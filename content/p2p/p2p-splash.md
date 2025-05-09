+++
title        = "P2P – Splash Page"
date         = 2025-05-09T13:28:24+12:00
draft        = false
section      = "p2p"
tags         = ["p2p"]
color_scheme = "terminal"
layout       = "simple"
+++

<div class="p2p-splash">

  <!-- Full-screen video background -->
  <video autoplay loop muted playsinline class="absolute inset-0 w-full h-full object-cover">
    <source src="/videos/p2p-bg-loop.mp4" type="video/mp4">
  </video>

  <!-- Static SVG fallback -->

<img
    src="/images/p2p-bg-fallback.svg"
    alt="P2P background fallback"
    class="absolute inset-0 w-full h-full object-cover"
  />

  <!-- Overlay: badge, tagline, buttons -->
  <div class="overlay">
    <div class="badge">{{< badge >}}GitHub Verified{{< /badge >}}</div>
    <h1 class="headline">
      100 % decentralized, offline-first communications
    </h1>
    <div class="cta-buttons">
      {{< button href="/p2p/get-started" >}}Get Started{{< /button >}}
      {{< button href="https://github.com/yourorg/p2p" >}}Audit Code on GitHub{{< /button >}}
      {{< button href="/download/tor" >}}Download via Tor{{< /button >}}
    </div>
  </div>

</div>
