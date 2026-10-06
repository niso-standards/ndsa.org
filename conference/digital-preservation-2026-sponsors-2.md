---
title: 2026 Digital Preservation Sponsors
layout: page
permalink: /conference/digital-preservation-2026/sponsors2/
---

<p><strong>The Planning Committee wishes to thank our sponsors for their support.</strong></p>

<h2>Gold Sponsor</h2>

<div class="sponsor-grid sponsor-grid-gold">

  <div class="sponsor-card sponsor-card-gold">
    <a class="sponsor-logo sponsor-logo-gold"
       href="https://preservica.com/"
       target="_blank"
       rel="noopener">
      <img
        src="{{ '/images/sponsors/Preservica_CMYK Logo.jpg' | relative_url }}"
        alt="Preservica logo"
      >
    </a>

    <div class="sponsor-name">Preservica</div>

    <a class="sponsor-button"
       href="https://preservica.com/"
       target="_blank"
       rel="noopener">
      Visit Sponsor →
    </a>
  </div>

</div>


<h2>Bronze Sponsors</h2>

<div class="sponsor-grid sponsor-grid-bronze">

  <div class="sponsor-card">
    <a class="sponsor-logo"
       href="https://aptrust.org/"
       target="_blank"
       rel="noopener">
      <img
        src="{{ '/images/sponsors/aptrust_logo.png' | relative_url }}"
        alt="APTrust logo"
      >
    </a>

    <div class="sponsor-name">APTrust</div>

    <a class="sponsor-button"
       href="https://aptrust.org/"
       target="_blank"
       rel="noopener">
      Visit Sponsor →
    </a>
  </div>


  <div class="sponsor-card">
    <a class="sponsor-logo"
       href="https://www.digitalbedrock.com/"
       target="_blank"
       rel="noopener">
      <img
        src="{{ '/images/sponsors/Digital-Bedrock_Tag.jpg' | relative_url }}"
        alt="Digital Bedrock logo"
      >
    </a>

    <div class="sponsor-name">Digital Bedrock</div>

    <a class="sponsor-button"
       href="https://www.digitalbedrock.com/"
       target="_blank"
       rel="noopener">
      Visit Sponsor →
    </a>
  </div>

</div>


<div class="sponsor-cta">
  <p>
    <strong>Interested in sponsoring
      <a href="https://ndsa.org/meetings/">Digital Preservation 2026</a>?</strong>
    Check out the
    <a href="https://docs.google.com/document/d/1aAnrNnPfJsjj-sEH_CYIYe-m4Zk0tXvi08KaiRvlZZI/edit?tab=t.0">2026 Sponsorship Prospectus</a>
    and contact us at ndsadigiprescochair2026 [at] gmail [dot] com.
  </p>
</div>


<style>

/* =========================================
   Sponsor grids
   ========================================= */

.sponsor-grid {
  display: grid;
  gap: 1.75rem;
  margin: 1.5rem 0 3.5rem;
}


/* Gold: one large, full-width card */

.sponsor-grid-gold {
  grid-template-columns: 1fr;
}


/* Bronze: two cards side by side */

.sponsor-grid-bronze {
  grid-template-columns: repeat(2, 1fr);
}


/* =========================================
   Sponsor cards
   ========================================= */

.sponsor-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;

  min-height: 300px;
  padding: 2rem 1.5rem 1.5rem;

  background: #fff;
  border: 1px solid #d9d9d9;
  border-radius: 6px;

  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.08);

  transition:
    transform 0.2s ease,
    box-shadow 0.2s ease;
}


/* Gold card is larger */

.sponsor-card-gold {
  min-height: 380px;
  padding: 3rem 2rem 2rem;
}


/* Subtle hover effect */

.sponsor-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 5px 14px rgba(0, 0, 0, 0.13);
}


/* =========================================
   Logo area
   ========================================= */

.sponsor-logo {
  display: flex;
  align-items: center;
  justify-content: center;

  width: 100%;
  height: 140px;

  margin-bottom: 1rem;
}


/* Larger logo area for Gold */

.sponsor-logo-gold {
  height: 210px;
}


.sponsor-logo img {
  display: block;

  max-width: 230px;
  max-height: 120px;

  width: auto;
  height: auto;

  object-fit: contain;
}


/* Larger Gold logo */

.sponsor-logo-gold img {
  max-width: 360px;
  max-height: 180px;
}


/* =========================================
   Sponsor name
   ========================================= */

.sponsor-name {
  margin: 0.5rem 0 1.25rem;

  font-size: 1.2rem;
  font-weight: 600;
}


/* Larger Gold sponsor name */

.sponsor-card-gold .sponsor-name {
  font-size: 1.4rem;
}


/* =========================================
   Sponsor link
   ========================================= */

.sponsor-button {
  display: inline-block;

  margin-top: auto;
  padding: 0.55rem 1.15rem;

  border: 1px solid #777;
  border-radius: 4px;

  text-decoration: none;
  font-size: 0.95rem;
}


.sponsor-button:hover {
  text-decoration: none;
}


/* =========================================
   Sponsorship information
   ========================================= */

.sponsor-cta {
  margin-top: 3rem;
  padding-top: 1.5rem;

  border-top: 1px solid #ddd;
}


/* =========================================
   Responsive layout
   ========================================= */

@media (max-width: 700px) {

  .sponsor-grid-bronze {
    grid-template-columns: 1fr;
  }

  .sponsor-card-gold {
    min-height: 320px;
  }

  .sponsor-logo-gold {
    height: 170px;
  }

  .sponsor-logo-gold img {
    max-width: 280px;
    max-height: 150px;
  }

}

</style>