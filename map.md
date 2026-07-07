---
layout: page
title: "Interactive map — Stefano Ninfole"
permalink: /map/
---

<section class="map-page">
  <p class="map-eyebrow">Interactive map</p>
  <h1 class="map-title">The role of residual emissions for the abatement choice of hard-to-abate industries</h1>
  <p class="map-note">Industrial plants in Germany and their cost-minimizing abatement technology. Click a plant for the full cost breakdown.</p>
  <aside class="map-disclaimer">
    <p><strong>A note on the cost figures.</strong> The costs shown here are not the actual costs of the firms displayed — real cost structures are proprietary and not publicly known, and no claim is made about any individual firm's costs. All figures are indicative estimates: cost projections for decarbonization technologies, taken from the techno-economic literature and applied to industrial plants in Germany. They show what abatement would cost <em>if</em> these estimated production costs applied — not what any firm actually pays.</p>
    <p>The estimates include the cost of residual emissions: every technology leaves some CO2 unabated, and the central question of the map is how much a plant would spend paying the carbon price for that non-abated CO2 under each technology.</p>
  </aside>
  <div class="map-frame">
    <iframe src="{{ '/assets/map/plants-map.html' | relative_url }}"
            title="Map of German industrial plants and their chosen abatement technology"
            loading="lazy"></iframe>
  </div>
  <p class="map-caption">From the working paper with Knut Einar Rosendahl and Franziska Holz. <a href="{{ '/' | relative_url }}#working-papers">Read the abstract</a>.</p>
</section>
