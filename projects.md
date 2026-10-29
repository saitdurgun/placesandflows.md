---
title: Projects
nav_order: 5
---

<style>
  .project {
    border: 1px solid rgba(128, 128, 128, 0.35);
    border-radius: 6px;
    margin: 1.5rem 0;
    overflow: hidden;
  }
  .project > summary {
    list-style: none;
    cursor: pointer;
    display: flex;
    gap: 1.25rem;
    align-items: flex-start;
    padding: 1rem;
  }
  .project > summary::-webkit-details-marker { display: none; }
  .project > summary:focus-visible { outline: 2px solid #ec6d1b; outline-offset: -2px; }
  .project-image {
    flex: 0 0 45%;
    width: 45%;
    aspect-ratio: 4 / 3;
    object-fit: cover;
    border-radius: 4px;
    margin: 0;
  }
  /* When opened: photo goes full width above the text, uncropped */
  .project[open] > summary { flex-direction: column; }
  .project[open] .project-image {
    flex-basis: auto;
    width: 100%;
    aspect-ratio: auto;
  }
  .project-intro h3 { margin-top: 0; }
  .project-meta { margin: 0.25rem 0 0.75rem; opacity: 0.75; font-size: 0.9em; }
  .project-intro p:last-child { margin-bottom: 0; }
  .project-toggle { color: #ec6d1b; font-weight: 600; }
  .project-toggle::after { content: "Read more ▾"; }
  .project[open] .project-toggle::after { content: "Show less ▴"; }
  .project-body { padding: 0 1rem 1rem; }
  .project-figure { display: block; width: 100%; border-radius: 4px; margin: 1rem 0; }
  .project-media-row { display: flex; gap: 1.25rem; align-items: center; margin: 0.5rem 0 1rem; }
  .project-media-row img { flex: 0 0 30%; width: 30%; border-radius: 4px; margin: 0; }
  .project-media-row p { margin: 0; }
  .project-body h4 {
    font-weight: 700;
    font-size: 1em !important;
    line-height: inherit;
    text-transform: none;
    letter-spacing: normal;
    margin: 1.5rem 0 0.5rem;
  }
  @media (max-width: 640px) {
    .project > summary { flex-direction: column; }
    .project-image { flex-basis: auto; width: 100%; aspect-ratio: 16 / 9; }
    .project-media-row { flex-direction: column; align-items: flex-start; }
    .project-media-row img { width: 60%; flex-basis: auto; }
  }
</style>

# Projects

Our projects sit at the intersection of people, place, and data. We work with industry partners, heritage organizations, municipalities, and tourism stakeholders to understand and improve how people experience places.

---

<details class="project">
  <summary>
    <img class="project-image" src="{{ '/assets/images/digikompas.jpg' | relative_url }}" alt="Visitors gathered around a 3D-printed model of Strijp-S at Dutch Design Week 2026">
    <div class="project-intro">
      <h3>Making urban complexity tangible</h3>
      <p class="project-meta">With SmartwayZ.NL at Dutch Design Week 2026</p>
      <p>SmartwayZ.NL came to the Places &amp; Flows Lab with a complex spatial challenge: the traffic situation around Strijp-S in Eindhoven. Together, we turned the data behind it into a 3D-printed model with projected data layers, and presented it at Dutch Design Week 2026 for everyone to explore.</p>
      <p><span class="project-toggle"></span></p>
    </div>
  </summary>
  <div class="project-body" markdown="1">

#### The challenge
Strijp-S is the heart of Dutch Design Week, but also one of the busiest and most complex places in Eindhoven to walk and cycle. On the Torenallee, pedestrians, terraces and cyclists share the same space. At its end, the Strijps Bultje viaduct carries the Ring road over a tangle of crossing routes, and the Ring separates Strijp-S from Strijp-T. The viaduct is nearing the end of its structural life, so the area faces choices that will shape it for decades.

#### How we worked together
SmartwayZ.NL brought the challenge and the questions behind it. We sat down together to decide what people needed to see to understand the area, and which data could show it. Our lab then translated that complex geospatial data into tangible insights: a physical model of the area, with data projected onto it layer by layer.

The goal was not to present a ready-made answer. It was to make the problem visible and understandable for everyone, so that people could start thinking about it together.

#### Why tangible data makes a difference
Paper maps and 2D screens ask people to imagine the real place. A physical model doesn’t. Visitors recognised the streets right away, gathered around the table and started discussing with each other. When a problem is easy to see and understand, everyone can join the conversation, not just experts. That is where better ideas and creative solutions begin.

*We believe better ideas emerge when data becomes tangible.*

#### Working with us
Do you have a geospatial challenge? You bring the question, and we sit down together to turn the data into insights everyone can see and understand. Contact us at [placesandflows@buas.nl](mailto:placesandflows@buas.nl).

  </div>
</details>

<details class="project">
  <summary>
    <img class="project-image" src="{{ '/assets/images/emotion_map.jpg' | relative_url }}" alt="Emotion map of Fort Sabina projected onto the Tangible Landscape">
    <div class="project-intro">
      <h3>Mapping how visitors feel at Fort Sabina</h3>
      <p class="project-meta">Emotion mapping at a heritage site</p>
      <p>People do not just move through places, they feel them. At Fort Sabina, we measured how visitors felt while exploring the fortress and its surroundings, and turned those measurements into emotion maps that show where people felt tense, excited or relaxed.</p>
      <p><span class="project-toggle"></span></p>
    </div>
  </summary>
  <div class="project-body" markdown="1">

#### The challenge
A walking route or a historic site can evoke moments of calm, excitement, stress or awe. For heritage managers, knowing where these moments happen is key to creating a visit that is not only efficient, but also meaningful and memorable. Visitor counts and surveys show where people go, but not how they feel along the way.

<img class="project-figure" src="{{ '/assets/images/emotion_map2.jpg' | relative_url }}" alt="Aerial view of Fort Sabina and its moat">

#### How we did it
<div class="project-media-row">
  <img src="{{ '/assets/images/shimmer.png' | relative_url }}" alt="Shimmer GSR+ device worn on the wrist, with sensors on two fingers">
  <p>Visitors wore the Shimmer GSR+, a wearable wrist device with finger sensors and a gold-standard tool for measuring skin conductance. It records subtle changes in sweating of the skin, one of the most sensitive indicators of emotional arousal. We combined these signals with GPS data, so every moment could be linked to a place on the site.</p>
</div>

We then projected the results onto a physical model of the fortress with our Tangible Landscape. This made it easy to see at a glance where visitors felt tense, excited or relaxed.

#### What it’s used for
The emotion maps help heritage managers understand how visitors respond to different spaces. They support decisions on redesigning visitor flows and improving the overall experience of the site.

  </div>
</details>

<!--
  To add a new project: copy everything from <details class="project"> to </details>,
  paste it below, and change the image path, title, meta line, intro and body text.
-->

---

## Current Research Areas

- **Tourism & Leisure** — Understanding visitor flows and emotional experiences at destinations
- **Spatial Planning** — Supporting urban and rural planning decisions with tangible data visualization
- **Climate Adaptation** — Visualizing flood risk, land-use change, and environmental impact
- **Cultural Heritage** — Helping heritage sites improve visitor experience through emotion mapping
- **Mobility** — Analyzing how people move through cities and landscapes

---

## Work With Us

Our research is driven by the interests of our institute and our students — in the form of thesis and course assignments — or commissioned by industry partners at commercial rates.

Interested in collaborating? Contact us at [placesandflows@buas.nl](mailto:placesandflows@buas.nl)
