---
permalink: /
title: ""
excerpt: ""
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %} 

<!-- Hero Section -->
<section id="home" class="hero-section">
  <div class="hero-content">
    <img src="{{ '/images/jc.jpg' | relative_url }}" alt="Chao Jiang" class="hero-avatar">
    <h1 class="hero-name">Chao Jiang (蒋超)</h1>
    <p class="hero-title">Ph.D. Student</p>
    <p class="hero-school">School of Computer Science</p>
    <p class="hero-university">University of Birmingham</p>
    <div class="hero-links">
      <a href="mailto:{{ site.author.email }}"><i class="fas fa-envelope"></i> Email</a>
      <a href="{{ site.author.googlescholar }}" target="_blank"><i class="fas fa-graduation-cap"></i> Google Scholar</a>
      <a href="https://github.com/{{ site.author.github }}" target="_blank"><i class="fab fa-github"></i> GitHub</a>
      <a href="{{ site.author.orcid }}" target="_blank"><i class="ai ai-orcid"></i> ORCID</a>
      <!-- <a href="#" class="rednote-link" data-image="{{ '/images/rednote.png' | relative_url }}"><i class="fas fa-book"></i> REDnote</a> -->
    </div>
  </div>
</section>


<!-- About Section --> 
<!--
<section id="about" class="section">
  <h2 class="section-title"><i class="fas fa-user"></i> About Me</h2>
  <div class="card-grid">
    <div class="card">
      <div class="card-header">
        <div class="card-icon"><i class="fas fa-user"></i></div>
        <div>
          <h3 class="card-title">Introduction</h3>
        </div>
      </div>
      <div class="card-content">
        <p>Hi there, I am Zhiyuan Su (Chinese name: 苏智渊), you can call me "Julian". I am currently a <strong>senior undergraduate</strong> at <a href="http://ai.ruc.edu.cn/" target="_blank">Gaoling School of Artificial Intelligence</a>, <a href="https://www.ruc.edu.cn/" target="_blank">Renmin University of China</a>.</p>
        <p>I was an exchange student at <a href="https://www.ucdavis.edu/" target="_blank">University of California, Davis</a> (Jan 2025 - Mar 2025) and a visiting research student at <a href="https://www.dal.ca/" target="_blank">Dalhousie University</a> (Jul 2025 - Oct 2025), sponsored by <a href="https://www.mitacs.ca/" target="_blank">Mitacs, Canada</a>.</p>
        <p>❗️<span style="color:red">I am actively seeking Ph.D. positions starting in Fall 2026. If you think my background is a good fit for you, please don't hesitate to contact me via <a href="zhiyuansurenminu@gmail.com" target="_blank">zhiyuansurenminu@gmail.com</a>!</span></p>
</div>
</div>
    <div class="card">
      <div class="card-header">
        <div class="card-icon"><i class="fas fa-flask"></i></div>
        <div>
          <h3 class="card-title">Research Interests</h3>
        </div>
      </div>
      <div class="card-content">
        <p>My research interests focus on <strong>reinforcement learning, sequential decision-making, continual learning, online learning, and controllable & personalized AI</strong>. In addition, I am also interested in board application of AI models. <strong>Recently, I am focusing on: </strong>1) sequential bidding ranking algorithms, 2) controllable model editing in generative models.</p>
        <p>My research aims to build <strong>intelligent systems that are elegant in theory and effective in practice</strong>, and provide credible solutions to the urgent needs of contemporary society.</p>
      </div>
    </div>
  </div>
</section>
--> 

<!-- About Section --> 
<section id="about" class="section">
  <h2 class="section-title"><i class="fas fa-user"></i> About Me</h2>

  <div class="card-grid">
    <div class="card">
      <div class="card-header">
        <div class="card-icon"><i class="fas fa-user"></i></div>
        <div>
          <h3 class="card-title">Introduction</h3>
        </div>
      </div>

      <div class="card-content">
        <p>
          <strong>Chao Jiang</strong> is a <strong>Ph.D. student</strong> at the
          <a href="https://www.birmingham.ac.uk/schools/computer-science" target="_blank">
            University of Birmingham
          </a>,
          supervised by
          <a href="https://sites.google.com/view/miqing-li/home" target="_blank">
            Dr. Miqing Li
          </a>
          (2022.09–present).
        </p>

        <p>
          His research interests include <strong>Artificial Intelligence</strong>,
          <strong>Machine Learning</strong>, <strong>Optimisation</strong>
          (Bayesian Optimisation and Evolutionary Algorithms), and
          <strong>Search-Based Software Engineering</strong>.
        </p>
      </div>
    </div>
  </div>
</section>


<!-- News Section -->

<section id="news" class="section">
  <h2 class="section-title"><i class="fas fa-newspaper"></i> News</h2>
  <div class="card">
    <div class="card-content">
    <div class="news-item">
      <div class="news-date">November 2025</div>
      <div class="news-content">
        Physically attended 
        <a href="https://aiia.seu.edu.cn/mla25/" target="_blank"><strong>MLA 2025</strong></a>
        conference at Nanjing, China.
      </div>
    </div>
    <div class="news-item">
      <div class="news-date">July 2025</div>
      <div class="news-content">
        Physically attended 
        <a href="https://gecco-2025.sigevo.org/HomePage" target="_blank">
          <strong>GECCO 2025</strong>
        </a>
        conference at Malaga, Spain.
      </div>
    </div>
    <div class="news-item">
    <div class="news-date">January 2025</div>
    <div class="news-content">
        <a href="https://doi.org/10.1145/3716504" target="_blank">
          <strong>Our work</strong>
        </a> 
        on multi-objectivising acquisition functions in Bayesian optimisation has been accepted by ACM Transactions on Evolutionary Learning and Optimization.</div>
    </div>
    <div class="news-item">
    <div class="news-date">December 2024</div>
    <div class="news-content">        
        <a href="https://doi.org/10.1609/aaai.v39i25.34909" target="_blank">
          <strong>Our work</strong>
        </a> 
        on batch Bayesian optimisation through a multi-objective approach has been accepted by AAAI'25!</div>
    </div>
    </div>
  </div>
</section>


<!-- Publications Section -->
<section id="publications" class="section">
  <h2 class="section-title"><i class="fas fa-file-alt"></i> Selected Publications</h2>
  <div class="paper-list">

    <div class="paper-item">
      <div class="paper-image-container">
        <img src="{{ '/images/TELO_MOEE.jpg' | relative_url }}" alt="MOEE Paper">
      </div>
      <div class="paper-content">
        <h3 class="paper-title">
          <a href="https://doi.org/10.1145/3716504" target="_blank">Multi-objectivising acquisition functions in Bayesian optimisation</a>
        </h3>
        <p class="paper-authors">
          <strong>Chao Jiang</strong>, Miqing Li
        </p>
        <div class="paper-meta">
          <span class="paper-tag conference">TELO</span>
          <span class="paper-tag"><a href="https://github.com/ChaoJiang52/TELO-MOEE" target="_blank">CODE</a></span>
          <!-- <span class="paper-tag">Multi-Objectivisation</span> -->
          <!-- <span class="paper-tag">Acquisition Function</span> -->
        </div>
      </div>
    </div>

    <div class="paper-item">
      <div class="paper-image-container">
        <img src="{{ '/images/AAAI_POEE.jpg' | relative_url }}" alt="POEE Paper">
      </div>
      <div class="paper-content">
        <h3 class="paper-title">
          <a href="https://doi.org/10.1609/aaai.v39i25.34909" target="_blank">Trading off quality and uncertainty through multi-objective optimisation in batch Bayesian optimisation</a>
        </h3>
        <p class="paper-authors"><strong>Chao Jiang</strong>, Miqing Li</p>
        <div class="paper-meta">
          <span class="paper-tag conference">AAAI 2025</span>
          <span class="paper-tag"><a href="https://github.com/ChaoJiang52/AAAI-POEE" target="_blank">CODE</a></span>
          <!-- <span class="paper-tag">Sequential Decision Making</span> -->
          <!-- <span class="paper-tag">Continual Learning</span> -->
        </div>
      </div>
    </div>

<!-- 
    <div class="paper-item">
      <div class="paper-image-container">
        <img src="{{ '/images/pcDE.png' | relative_url }}" alt="pcDE-ASL Paper">
      </div>
      <div class="paper-content">
        <h3 class="paper-title">
          <a href="10.1109/JSEN.2021.3115471" target="_blank">Matching Sensor Ontologies with Multi-Context Similarity Measure and Parallel Compact Differential Evolution Algorithm</a>
        </h3>
        <p class="paper-authors">Xingsi Xue, <strong>Chao Jiang</strong></p>
        <div class="paper-meta">
          <span class="paper-tag conference">IEEE Sensors Journal</span>
        </div>
      </div>
    </div>

    <div class="paper-item">
      <div class="paper-image-container">
        <img src="{{ '/images/WWW.png' | relative_url }}" alt="WWW Paper">
      </div>
      <div class="paper-content">
        <h3 class="paper-title">
          <a href="https://doi.org/10.1145/3442442.3451138" target="_blank">Artificial neural network based sensor ontology matching technique</a>
        </h3>
        <p class="paper-authors">Xingsi Xue, <strong>Chao Jiang</strong>, Chaofan Yang, Hai Zhu, Cong Hu</p>
        <div class="paper-meta">
          <span class="paper-tag conference">WWW 2021</span>
        </div>
      </div>
    </div>

    <div class="paper-item">
      <div class="paper-image-container">
        <img src="{{ '/images/BIBM.png' | relative_url }}" alt="BIBM Paper">
      </div>
      <div class="paper-content">
        <h3 class="paper-title">
          <a href="10.1109/BIBM49941.2020.9313345" target="_blank">Matching biomedical ontologies with long short-term memory networks</a>
        </h3>
        <p class="paper-authors"><strong>Chao Jiang</strong>, Xingsi Xue</p>
        <div class="paper-meta">
          <span class="paper-tag conference">BIBM 2020</span>
        </div>
      </div>
    </div>
 -->

  </div>
</section>


<!-- Teaching Associate Section -->

<section id="teaching" class="section">
  <h2 class="section-title"><i class="fas fa-chalkboard-teacher"></i> Teaching Associate</h2>

  <div class="card">
    <div class="card-content">

      <div class="news-item">
        <div class="news-date">Autumn 2023, Autumn 2025</div>
        <div class="news-content"><strong>Algorithms for Data Science</strong></div>
      </div>

      <div class="news-item">
        <div class="news-date">Autumn 2023, Autumn 2024</div>
        <div class="news-content"><strong>Programming for Data Science / AI Programming</strong></div>
      </div>

      <div class="news-item">
        <div class="news-date">Spring 2023, Spring 2024, Spring 2025</div>
        <div class="news-content"><strong>Artificial Intelligence 2</strong></div>
      </div>

      <div class="news-item">
        <div class="news-date">Spring 2023</div>
        <div class="news-content"><strong>Artificial Intelligence 1 &amp; Artificial Intelligence and Machine Learning</strong></div>
      </div>

      <div class="news-item">
        <div class="news-date">Autumn 2022</div>
        <div class="news-content"><strong>Object-Oriented Programming &amp; Software Workshop 1</strong></div>
      </div>

    </div>
  </div>
</section>



<!-- Honors and Awards Section -->


<!-- 

<section id="honors" class="section">

  <h2 class="section-title"><i class="fas fa-trophy"></i> Honors and Awards</h2>

  <div class="card">

    <div class="card-content">

      <div class="news-item">

        <div class="news-date">Nov 2025</div>

        <div class="news-content">Qiushi Academic International Support Program <span class="highlight-red">[Highest Funding]</span></div>

      </div>

      <div class="news-item">

        <div class="news-date">Jul 2025</div>

        <div class="news-content">SIGKDD-supported KDD 2025 Student Travel Award <span class="highlight-red">[1,000 USD]</span></div>

      </div>

      <div class="news-item">

        <div class="news-date">Jun 2025</div>

        <div class="news-content">Presidential Scholarship <span class="highlight-red">[40,000 CNY]</span></div>

      </div>

      <div class="news-item">

        <div class="news-date">Jan 2025</div>

        <div class="news-content">Mitacs Globalink Internship Scholarship <span class="highlight-red">[6,000 CAD]</span></div>

      </div>

      <div class="news-item">

        <div class="news-date">Dec 2024</div>

        <div class="news-content"><span class="highlight-red">[National Second Prize]</span> 19th "Challenge Cup" National Undergraduate Curricular Academic Science and Technology Works</div>

      </div>

    </div>

  </div>

</section>
 -->



<!-- Education Section -->

<!-- 
<section id="education" class="section">

  <h2 class="section-title"><i class="fas fa-graduation-cap"></i> Education</h2>

  <div class="list-section">

    <div class="list-item">

      <div class="list-item-logo">

        <img src="{{ '/images/ucdavis_logo.png' | relative_url }}" alt="UC Davis">

      </div>

      <div class="list-item-content">

        <div class="list-item-date">Jan 2025 – Mar 2025</div>

        <div class="list-item-title">Exchange, University of California, Davis</div>

        <div class="list-item-desc">Major: Mathematics & Statistics<br>Graduated with Academic Perfection</div>

      </div>

    </div>

    <div class="list-item">

      <div class="list-item-logo">

        <img src="{{ '/images/ruc_logo.png' | relative_url }}" alt="RUC">

      </div>

      <div class="list-item-content">

        <div class="list-item-date">Sep 2022 – Present</div>

        <div class="list-item-title">Gaoling School of Artificial Intelligence, Renmin University of China</div>

        <div class="list-item-desc">Bachelor of Engineering in Artificial Intelligence<br>Supervisors: <a href="https://gsai.ruc.edu.cn/qiqi" target="_blank">Dr. Qi Qi</a>, <a href="https://pinkfloyd1989.github.io/Xiao_Zhang/" target="_blank">Dr. Xiao Zhang</a></div>

      </div>

    </div>

  </div>

</section>
 -->


<!-- Work Experience Section -->

<!-- 
<section id="experience" class="section">

  <h2 class="section-title"><i class="fas fa-briefcase"></i> Work Experiences</h2>

  <div class="list-section">

    <div class="list-item">

      <div class="list-item-logo">

        <img src="{{ '/images/dal_logo.png' | relative_url }}" alt="Dalhousie">

      </div>

      <div class="list-item-content">

        <div class="list-item-date">Jul 2025 – Oct 2025 | Mitacs Research Intern </div>

        <div class="list-item-title">Faculty of Computer Science, Dalhousie University</div>

        <div class="list-item-desc">

          Visiting student at <a href="https://web.cs.dal.ca/~gaw/" target="_blank">Dalhousie Applied Machine Learning Research Lab (DAMLR)</a><br>

          Supervisor: <a href="https://wuga214.github.io/" target="_blank">Dr. Ga Wu</a>

        </div>

      </div>

    </div>

    <div class="list-item">

      <div class="list-item-logo">

        <img src="{{ '/images/baidu_color.png' | relative_url }}" alt="Baidu">

      </div>

      <div class="list-item-content">

        <div class="list-item-date">May 2024 – Sep 2024 | Summer Intern</div>

        <div class="list-item-title">Baidu Inc.</div>

        <div class="list-item-desc">Pinecone Talent Elite Project</div>

      </div>

    </div>

  </div>
</section>
 -->

<!-- Services Section -->

<!-- 
<section id="services" class="section">

  <h2 class="section-title"><i class="fas fa-handshake"></i> Services</h2>

  <div class="card-grid">

    <div class="card">

      <div class="card-header">

        <div class="card-icon"><i class="fas fa-gavel"></i></div>

        <div>

          <h3 class="card-title">Reviewer</h3>

        </div>

      </div>

      <div class="card-content">

        <p><strong>Reviewer</strong>, KDD 2025, WWW 2025.</p>

      </div>

    </div>

  </div>

</section>
 -->


<!-- Beyond Academics Section -->

<!-- 
<section id="interests" class="section">

  <h2 class="section-title"><i class="fas fa-palette"></i> Beyond Academics</h2>

  <div class="card-grid">

    <div class="card">

      <div class="card-header">

        <div class="card-icon"><i class="fas fa-music"></i></div>

        <div>

          <h3 class="card-title">Music & Arts</h3>

        </div>

      </div>

      <div class="card-content">

        <p>I love <strong>music, literature, travel and badminton</strong>. I am a <strong>campus singer</strong> at Renmin University of China and have been invited to participate in various concerts and music festivals at RUC.</p>

        <p>I am also a <strong>musician</strong> at <strong>NetEase Cloud Music</strong>, and my stage name is <a href="http://music.163.com/#/artist?id=36180214" target="_blank" style="color: var(--ruc-red);">Ayinor</a>.</p>

      </div>

    </div>

</div>

</section>
 -->