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
      <br>
      <Strong> Rob's Website </strong>
      https://www.bedform.org/ 
      
    </div>
  </section>

<div class="portfolio">

  <section class="hero">
    <div class="eyebrow">Geology · Planetary Science · Research</div>

    <h1>Tyler Roscoe</h1>

    <p>
      Exploring terrestrial and icy worlds, their surface processes, resources, and habitability.
       
    </p>

    <a class="portfolio-button" href="#research">Explore My Research</a>
    <a class="portfolio-button" href="RoscoeCV.pdf">View My CV</a>
  </section>

  <section class="portfolio-section" id="research">
    <h2>About Me</h2>

    <p>
    I am a geologist at my core, but I aim to be a multidisciplinary planetary scientist. As undergraduate in addition to geology I studied both physics, and astronomy. With my research I bring in a broad mindset. You can check out my CV for a list of my multidisciplinary experiences. At the moment most of the questions I am trying to answer involve the planet Mars. 
    </p>

    <div class="interests">
      <div class="interest">Terrestrial Worlds: Venus, Earth, Mars, Titan</div>
      <div class="interest">Icy Worlds and Polar Regions</div>
      <div class="interest">Surface Processes</div>
      <div class="interest">Applied Geophysics</div>
      <div class="interest">Applied Geochemistry</div>
      <div class="interest">Resources & Habitability</div>
    </div>
  </section>



 <section class="portfolio-section" id="field-work">
    <h2>My View on Studying Planets</h2>

    <p>
      I think field experiences are an important part of understanding
      broader planetary science questions. Before one can think of other worlds, they should start with their own. 
    </p>

    <img
      class="field-photo"
      src="images/TylerinYellowstoneFieldCamp.jpg"
      alt="Tyler Roscoe at Yellowstone"
    >

    <p class="photo-caption">
      At Yellowstone National Park (Field Course).
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
      <p>
      <strong> LinkedIn </strong>
      <br>
      https://www.linkedin.com/in/tyler-roscoe/
      </p>
    </div>
  </section>

</div>
