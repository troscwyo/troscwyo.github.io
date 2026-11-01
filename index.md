---
layout: default
---
{% include nav.html %}
<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}">
<style>
  .portfolio {
    max-width: 1050px;
    margin: 0 auto;
    color: #263746;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  }

  .portfolio * {
    box-sizing: border-box;
  }

  .hero {
    background: #172b3a;
    color: white;
    padding: 65px 45px;
    border-radius: 12px;
    margin: 25px 0 45px;
  }

  .hero .eyebrow {
    color: #b7c9d5;
    letter-spacing: 3px;
    font-size: 12px;
    font-weight: 700;
    text-transform: uppercase;
  }

  .hero h1 {
    color: white;
    font-size: clamp(36px, 6vw, 58px);
    line-height: 1.1;
    margin: 20px 0;
  }

  .hero p {
    color: #d5e0e7;
    font-size: 18px;
    line-height: 1.7;
    max-width: 650px;
  }

  .hero .subtitle {
    color: #c0d1dc;
    font-size: 15px;
  }

  .portfolio-section {
    margin: 45px 0;
  }

  .portfolio-section h2 {
    color: #172b3a;
    font-size: 25px;
    border-bottom: 2px solid #d9e2e8;
    padding-bottom: 12px;
    margin-bottom: 20px;
  }

  .portfolio-section p {
    font-size: 16px;
    line-height: 1.8;
  }

  .interests {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(190px, 1fr));
    gap: 14px;
    margin-top: 22px;
  }

  .interest {
    background: #f1f5f7;
    border-left: 4px solid #8b9eaa;
    padding: 18px;
    border-radius: 5px;
    font-weight: 600;
  }

  .profile-card {
    background: #f1f5f7;
    border-radius: 9px;
    padding: 25px;
    line-height: 1.8;
  }

  .portfolio-button {
    display: inline-block;
    background: #263f50;
    color: white !important;
    text-decoration: none !important;
    padding: 12px 20px;
    border-radius: 5px;
    margin: 8px 8px 8px 0;
    font-weight: 600;
  }

  .portfolio-button:hover {
    background: #426277;
  }

  .field-photo {
    width: 100%;
    max-height: 520px;
    object-fit: cover;
    border-radius: 10px;
    display: block;
  }

  .photo-caption {
    color: #71818c;
    font-size: 13px !important;
    margin-top: 10px;
  }

  .portfolio-footer {
    border-top: 1px solid #d9e2e8;
    padding: 25px 0;
    margin-top: 55px;
    color: #71818c;
    font-size: 13px;
    text-align: center;
  }

  @media (max-width: 600px) {
    .hero {
      padding: 40px 24px;
    }
  }
</style>

<div class="portfolio">

  <section class="hero">
    <div class="eyebrow">Geology · Planetary Science · Research</div>

    <h1>Tyler Roscoe</h1>

    <p class="subtitle">
      MS Student · Department of Geology & Geophysics
      <br>
      University of Wyoming
    </p>

    <p>
      Exploring terrestrial and icy worlds through the study of
      planetary surface processes, resources, and habitability.
    </p>

    <a class="portfolio-button" href="#research">Explore My Research</a>
    <a class="portfolio-button" href="RoscoeCV.pdf">View My CV</a>
  </section>

  <section class="portfolio-section" id="research">
    <h2>Research Interests</h2>

    <p>
      I am a Master's student in Geology at the University of Wyoming,
      working with Dr. Robert Mahon. My interests center on terrestrial
      and icy worlds throughout our solar system, with a focus on the
      processes that shape planetary surfaces and influence the
      availability of resources and potential habitability.
    </p>

    <div class="interests">
      <div class="interest">Planetary Geology</div>
      <div class="interest">Icy Worlds</div>
      <div class="interest">Surface Processes</div>
      <div class="interest">Planetary Resources</div>
      <div class="interest">Habitability</div>
    </div>
  </section>

  <section class="portfolio-section">
    <h2>Academic Background</h2>

    <div class="profile-card">
      <strong>Master of Science Student in Geology</strong>
      <br>
      University of Wyoming
      <br>
      Department of Geology & Geophysics
      <br>
      <br>
      <strong>Research Advisor:</strong>
      Dr. Robert Mahon
    </div>
  </section>

 <section class="portfolio-section" id="field-work">
    <h2>Field Work</h2>

    <p>
      Field experiences are an important part of understanding
      Earth's geological processes and connecting observations
      in the field with broader planetary science questions.
    </p>

    <img
      class="field-photo"
      src="images/TylerinYellowstoneFieldCamp.jpg"
      alt="Tyler Roscoe during fieldwork at Yellowstone"
    >

    <p class="photo-caption">
      Fieldwork at Yellowstone National Park.
    </p>
  </section>

  <section class="portfolio-section" id="cv">
    <h2>Curriculum Vitae & Resources</h2>

    <p>
      Learn more about my academic background and the
      University of Wyoming Department of Geology & Geophysics.
    </p>

    <a class="portfolio-button" href="RoscoeCV.pdf">
      Download My CV
    </a>

    <a class="portfolio-button"
       href="https://www.uwyo.edu/geolgeophys/"
       target="_blank"
       rel="noopener noreferrer">
      UW Geology & Geophysics
    </a>
  </section>

  <section class="portfolio-section" id="contact">
    <h2>Get in Touch</h2>
    
    <div class="profile-card">
      <p>
        Interested in my research or want to connect?
        Feel free to reach out.
      </p>

      <a href="mailto:troscoe@uwyo.edu">
        troscoe@uwyo.edu
      </a>
    </div>
  </section>

  <footer class="portfolio-footer">
    Tyler Roscoe · University of Wyoming
  </footer>

</div>
