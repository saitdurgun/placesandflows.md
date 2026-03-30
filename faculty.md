---
title: Faculty
layout: default
nav_order: 2
description: "Faculty"
permalink: /faculty.html
---

<style>
  .filter-container {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 10px;
    margin-bottom: 30px;
    flex-wrap: wrap;
  }

  .filter-label {
    font-weight: 600;
    font-size: 1.1em;
  }

  .filter-select {
    padding: 8px 12px;
    font-size: 1em;
    border: 1px solid #ccc;
    border-radius: 8px;
    background-color: #f8f9fa;
    color: #333;
    transition: border-color 0.3s ease, box-shadow 0.3s ease;
  }

  .filter-select:hover,
  .filter-select:focus {
    border-color: #0066cc;
    box-shadow: 0 0 5px rgba(0, 102, 204, 0.4);
    outline: none;
  }
</style>


# Faculty

Our teaching team brings international diversity and strong industry expertise to the classroom. Many of our lecturers are actively involved in the industry, working part-time alongside their teaching roles. This keeps our curriculum closely aligned with real-world developments and the latest tools in data science and AI. At the same time, most faculty members also hold PhDs and contribute to academic research, ensuring a solid foundation in theory. We maintain high standards to challenge and prepare students for careers at the cutting edge of the field.

<div class="filter-container">
    <label for="expertise-filter" class="filter-label">Filter by expertise:</label>
    <select id="expertise-filter" class="filter-select" onchange="filterFaculty()">
    <option value="all">All</option>
    <option value="ai">Artificial Intelligence</option>
    <option value="business">Business & Digital Transformation</option>
    <option value="compute">Cloud & Compute Systems</option>
    <option value="cv">Computer Vision</option>
    <option value="control">Control Systems</option>
    <option value="data-eng">Data Engineering</option>
    <option value="ds">Data Science</option>
    <option value="dl">Deep Learning</option>
    <option value="mlops">Deployment & MLOps</option>
    <option value="ethics">Ethics, Philosophy & Society</option>
    <option value="games">Games</option>
    <option value="gen-ai">Generative AI</option>
    <option value="responsible-ai">Human-Centered & Responsible AI</option>
    <option value="ml">Machine Learning</option>
    <option value="nlp">Natural Language Processing</option>
    <option value="project">Project Management & Innovation</option>
    <option value="rl">Reinforcement Learning</option>
    <option value="research">Research Methods</option>
    <option value="robotics">Robotics</option>
    </select>
</div>

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 40px;">

<!-- Dean -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="ai,compute,ds,dl,mlops,gen-ai,ml,rl,robotics">
    <img src="assets/images/faculty/dean.jpg" alt="Dean van Aswegen" style="width: 150px; border-radius: 50%;">
    <h3>Dean van Aswegen, M.Sc.</h3>
    <p>Senior Lecturer</p>
    <p><a href="/faculty/dean-van-aswegen.html">View Profile</a></p>
</div>

<!-- Peiman -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="ai,ds,dl,ml,nlp">
    <img src="assets/images/faculty/peiman.png" alt="Peiman Barnaghi" style="width: 150px; border-radius: 50%;">
    <h3>Peiman Barnaghi, Ph.D.</h3>
    <p>Lecturer</p>
    <p><a href="/faculty/peiman-barnaghi.html">View Profile</a></p>
</div>

<!-- Irene -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="ai,ds,dl,ethics,responsible-ai,ml">
    <img src="assets/images/faculty/irene.jpg" alt="Irene van Blerck" style="width: 150px; border-radius: 50%;">
    <h3>Irene van Blerck, M.Sc.</h3>
    <p>Lecturer</p>
    <p><a href="/faculty/irene-van-blerck.html">View Profile</a></p>
</div>

<!-- Myrthe -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="ai,ds,responsible-ai,ml,nlp,project">
    <img src="assets/images/faculty/myrthe.jpg" alt="Myrthe Buckens" style="width: 150px; border-radius: 50%;">
    <h3>Myrthe Buckens, M.A.</h3>
    <p>Lecturer</p>
    <p><a href="/faculty/myrthe-buckens.html">View Profile</a></p>
</div>

<!-- Mohsen -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="ai,business,control,data-eng,ds,ml,rl">
    <img src="assets/images/faculty/mohsen.jpg" alt="Mohsen Davarynejad" style="width: 150px; border-radius: 50%;">
    <h3>Mohsen Davarynejad, Ph.D.</h3>
    <p>Senior Lecturer</p>
    <p><a href="/faculty/mohsen-davarynejad.html">View Profile</a></p>
</div>

<!-- Mekselina -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="ai,ethics,gen-ai,responsible-ai,ml,nlp">
    <img src="assets/images/faculty/mekselina.jpg" alt="Mekselina Doganc" style="width: 150px; border-radius: 50%;">
    <h3>Mekselina Doganc, M.A.</h3>
    <p>Lecturer</p>
    <p><a href="/faculty/mekselina-doganc.html">View Profile</a></p>
</div>

<!-- Jason -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="compute,data-eng,mlops,project,robotics">
    <img src="assets/images/faculty/jason.jpg" alt="Jason Harty" style="width: 150px; border-radius: 50%;">
    <h3>Jason Harty, B.Sc.</h3>
    <p>Lecturer</p>
    <p><a href="/faculty/jason-harty.html">View Profile</a></p>
</div>

<!-- Avril -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="">
    <img src="assets/images/faculty/avril.jpg" alt="Avril Hayden" style="width: 150px; border-radius: 50%;">
    <h3>Avril Hayden, M.Sc.</h3>
    <p>Lecturer</p>
    <p><a href="/faculty/avril-hayden.html">View Profile</a></p>
</div>

<!-- Bert -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="games">
    <img src="assets/images/faculty/bert.png" alt="Bert Heesakkers" style="width: 150px; border-radius: 50%;">
    <h3>Bert Heesakkers, M.Sc.</h3>
    <p>Lecturer</p>
    <p><a href="/faculty/bert-heesakkers.html">View Profile</a></p>
</div>

<!-- Bram -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="games,responsible-ai,research">
    <img src="assets/images/faculty/bram.png" alt="Bram Heijligers" style="width: 150px; border-radius: 50%;">
    <h3>Bram Heijligers, M.Sc.</h3>
    <p>Lecturer</p>
    <p><a href="/faculty/bram-heijligers.html">View Profile</a></p>
</div>

<!-- Shival -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="ai,business,cv,dl,ml,robotics">
    <img src="assets/images/faculty/shival.png" alt="Shival Indermun" style="width: 150px; border-radius: 50%;">
    <h3>Shival Indermun, Ph.D.</h3>
    <p>Lecturer</p>
    <p><a href="/faculty/shival-indermun.html">View Profile</a></p>
</div>

<!-- Zhanna -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="business,ethics,responsible-ai,project">
    <img src="assets/images/faculty/zhanna.jpeg" alt="Zhanna Kozlova" style="width: 150px; border-radius: 50%;">
    <h3>Zhanna Kozlova, M.A., M.Sc.</h3>
    <p>Lecturer</p>
    <p><a href="/faculty/zhanna-kozlova.html">View Profile</a></p>
</div>

<!-- Margot -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="business,ds,ethics,responsible-ai,research,robotics">
    <img src="assets/images/faculty/margot.jpg" alt="Margot Neggers" style="width: 150px; border-radius: 50%;">
    <h3>Margot Neggers, Ph.D.</h3>
    <p>Lecturer</p>
    <p><a href="/faculty/margot-neggers.html">View Profile</a></p>
</div>

<!-- Martha -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="ai,ds,dl,ml,mlops,compute">
    <img src="assets/images/faculty/martha.jpg" alt="Martha Nikolaou" style="width: 150px; border-radius: 50%;">
    <h3>Martha Nikolaou, P.D.Eng.</h3>
    <p>Lecturer</p>
    <p><a href="/faculty/martha-nikolaou.html">View Profile</a></p>
</div>

<!-- Alican -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="ai,cv,ds,dl,gen-ai,ml,research">
    <img src="assets/images/faculty/alican.JPG" alt="Alican Noyan" style="width: 150px; border-radius: 50%;">
    <h3>Alican Noyan, Ph.D.</h3>
    <p>Senior Lecturer</p>
    <p><a href="/faculty/alican-noyan.html">View Profile</a></p>
</div>

<!-- Frank -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="business">
    <img src="assets/images/faculty/frank.jpeg" alt="Frank Peters" style="width: 150px; border-radius: 50%;">
    <h3>Frank Peters, Ph.D.</h3>
    <p>Program Manager</p>
    <p><a href="/faculty/frank-peters.html">View Profile</a></p>
</div>

<!-- Elavendan -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="ai,business,ds,gen-ai,ml,project">
    <img src="assets/images/faculty/elavendan.jpg" alt="Elavendan Rajendran" style="width: 150px; border-radius: 50%;">
    <h3>Elavendan Rajendran, MBA</h3>
    <p>Lecturer</p>
    <p><a href="/faculty/elavendan-rajendran.html">View Profile</a></p>
</div>

<!-- Karna -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="ai,cv,ds,dl,mlops,ml">
    <img src="assets/images/faculty/karna.jpg" alt="Karna Rewatkar" style="width: 150px; border-radius: 50%;">
    <h3>Karna Rewatkar, M.Sc.</h3>
    <p>Lecturer</p>
    <p><a href="/faculty/karna-rewatkar.html">View Profile</a></p>
</div>

<!-- Arash -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="ai,control,ds,dl,ml,robotics">
    <img src="assets/images/faculty/arash.jpeg" alt="Arash Sadeghzadeh" style="width: 150px; border-radius: 50%;">
    <h3>Arash Sadeghzadeh, Ph.D.</h3>
    <p>Senior Lecturer</p>
    <p><a href="/faculty/arash-sadeghzadeh.html">View Profile</a></p>
</div>

<!-- Carlos -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="ai,games">
    <img src="assets/images/faculty/carlos.jpg" alt="Carlos Pereira Santos" style="width: 150px; border-radius: 50%;">
    <h3>Carlos Pereira Santos, Ph.D.</h3>
    <p>Professor</p>
    <p><a href="/faculty/carlos-pereira-santos.html">View Profile</a></p>
</div>

<!-- Edirlei -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="ai,cv,dl,games,gen-ai,ml">
    <img src="assets/images/faculty/edirlei.png" alt="Edirlei Soares de Lima" style="width: 150px; border-radius: 50%;">
    <h3>Edirlei Soares de Lima, Ph.D.</h3>
    <p>Lecturer</p>
    <p><a href="/faculty/edirlei-soares-de-lima.html">View Profile</a></p>
</div>

<!-- Tsegaye -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="ai,dl,gen-ai,ml,nlp,research">
    <img src="assets/images/faculty/tsegaye.jpg" alt="Tsegaye Misikir Tashu" style="width: 150px; border-radius: 50%;">
    <h3>Tsegaye Misikir Tashu, Ph.D.</h3>
    <p>Lecturer</p>
    <p><a href="/faculty/tsegaye-misikir-tashu.html">View Profile</a></p>
</div>

<!-- Uther -->
<div style="flex: 0 1 250px; text-align: center;" data-expertise="compute,data-eng,mlops,games">
    <img src="assets/images/faculty/uther.png" alt="Uther Tlas" style="width: 150px; border-radius: 50%;">
    <h3>Uther Tlas</h3>
    <p>Lecturer</p>
    <p><a href="/faculty/uther-tlas.html">View Profile</a></p>
</div>

</div>

<script>
function filterFaculty() {
  const selected = document.getElementById('expertise-filter').value;
  const cards = document.querySelectorAll('[data-expertise]');

  cards.forEach(card => {
    const expertise = card.getAttribute('data-expertise');
    if (selected === 'all' || (expertise && expertise.includes(selected))) {
      card.style.display = 'block';
    } else {
      card.style.display = 'none';
    }
  });
}
</script>