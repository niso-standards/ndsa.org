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


<!--
<h2>Silver Sponsors</h2>

<div class="sponsor-grid sponsor-grid-silver">

  <div class="sponsor-card sponsor-card-silver">

    <a class="sponsor-logo sponsor-logo-silver"
       href="SPONSOR-URL"
       target="_blank"
       rel="noopener">

      <img
        src="{{ '/images/sponsors/SPONSOR-LOGO.png' | relative_url }}"
        alt="Sponsor Name logo"
      >

    </a>

    <div class="sponsor-name">Sponsor Name</div>

    <a class="sponsor-button"
       href="SPONSOR-URL"
       target="_blank"
       rel="noopener">
      Visit Sponsor →
    </a>

  </div>

</div>
-->


<h2>Bronze Sponsors</h2>

<div class="sponsor-grid sponsor-grid-bronze">

  <div class="sponsor-card sponsor-card-bronze">

    <a class="sponsor-logo sponsor-logo-bronze"
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


  <div class="sponsor-card sponsor-card-bronze">

    <a class="sponsor-logo sponsor-logo-bronze"
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
    <strong>
      Interested in sponsoring
      <a href="https://ndsa.org/meetings/">Digital Preservation 2026</a>?
    </strong>

    Check out the
    <a href="https://docs.google.com/document/d/1aAnrNnPfJsjj-sEH_CYIYe-m4Zk0tXvi08KaiRvlZZI/edit?tab=t.0">
      2026 Sponsorship Prospectus
    </a>
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

.sponsor-grid-gold {
  grid-template-columns: 1fr;
}

.sponsor-grid-silver {
  grid-template-columns: repeat(2, 1fr);
}

.sponsor-grid-bronze {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1.75rem;
}


/* =========================================
   Base sponsor card
   ========================================= */

.sponsor-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;

  padding: 2rem 1.5rem 1.5rem;

  background: #fff;
  border: 1px solid #d9d9d9;
  border-radius: 6px;

  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.08);

  transition:
    transform 0.2s ease,
    box-shadow 0.2s ease;
}

.sponsor-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 5px 14px rgba(0, 0, 0, 0.13);
}


/* =========================================
   Gold
   ========================================= */

.sponsor-card-gold {
  min-height: 420px;
  padding: 3rem 2.5rem 2.5rem;
}

.sponsor-logo-gold {
  height: 230px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.sponsor-logo-gold img {
  max-width: 600px;
  max-height: 280px;
  width: auto;
  height: auto;
}

.sponsor-card-gold .sponsor-name {
  font-size: 1.7rem;
}


/* =========================================
   Silver
   ========================================= */

.sponsor-card-silver {
  min-height: 360px;
}

.sponsor-logo-silver {
  height: 190px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.sponsor-logo-silver img {
  max-width: 450px;
  max-height: 220px;
  width: auto;
  height: auto;
}

.sponsor-card-silver .sponsor-name {
  font-size: 1.4rem;
}


/* =========================================
   Bronze
   ========================================= */

.sponsor-card-bronze {
  width: 280px;
  min-height: 280px;
}

.sponsor-logo-bronze {
  height: 145px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.sponsor-logo-bronze img {
  max-width: 300px;
  max-height: 150px;
  width: auto;
  height: auto;
}

.sponsor-card-bronze .sponsor-name {
  font-size: 1.15rem;
}


/* =========================================
   Sponsor name
   ========================================= */

.sponsor-name {
  margin: 0.5rem 0 1.25rem;
  font-weight: 600;
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

@media (max-width: 800px) {

  .sponsor-grid-silver {
    grid-template-columns: repeat(2, 1fr);
  }

}


@media (max-width: 550px) {

  .sponsor-grid-silver {
    grid-template-columns: 1fr;
  }

  .sponsor-card-gold {
    min-height: 340px;
  }

  .sponsor-logo-gold {
    height: 190px;
  }

  .sponsor-logo-gold img {
    max-width: 90%;
    max-height: 200px;
  }

  .sponsor-card-bronze {
    width: 100%;
    max-width: 280px;
  }

}

</style>