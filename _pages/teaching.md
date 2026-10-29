---
title: 'Teaching'
layout: splash
permalink: /teaching/
header:
  overlay_image: /images/splash.png
  text_color: black
---

## Courses and Workshops

### 14:180:429/16:180:562 Water and Wastewater Treatment

This course ([syllabus](https://drive.google.com/file/d/19XzQ_lioHbF59835jCJ6B5mjcsI5ftpH/view?usp=drive_link)) covers engineering processes commonly used for drinking water and wastewater treatment, as well as topics of emerging concern. Key topics include drinking water and wastewater quality criteria, water chemistry, integration of unit processes into full scale treatment facilities, reactor design, coagulation, flocculation, sedimentation, filtration, disinfection, water softening, microbiology and biological wastewater treatment, oxidation-reduction processes in treatment, nutrient removal, and residual solids management. A design module is also included that demonstrate the use of process simulation software.

<br>
<img src='/images/teaching/water_wastewater_treatment.png#center' alt='Water and Wastewater Treatment' width='60%' id='image'>

### 11:117:333 Environmental Engineering Analysis Tools

This course ([syllabus](https://drive.google.com/file/d/1h4p2mwM5upQ1TxUCPCIX9dczW7-PTzBg/view?usp=sharing)) applies state-of-the-art environmental engineering tools in analyzing problems and creating solutions and designs. Tools may vary with current engineering practice, but generally cover applications for automated data organization, statistical analysis, modeling, and visualization.

### 16:180:611 Sustainable Design

Through this course ([syllabus](https://drive.google.com/file/d/1X2lymRGmW4bngyPC34sctMACFFi6wT9n/view?usp=sharing)), students will develop an understanding of quantitative sustainable design (QSD) and how to navigate engineering decision-making. Students will learn methods and tools for economic (techno-economic analysis, TEA; life cycle costing, LCC) and environmental (life cycle assessment, LCA) sustainability assessments, and how to link these tools to engineering design decisions under uncertainty. Students will apply these tools to design their engineered systems of interest, with special attention to water and energy infrastructure, water quality processes, resource recovery, green chemistry, and bioenergy/bioproducts.

<br>
<img src='/images/teaching/sustainable_design.png#center' alt='Quantitative Sustainable Design' width='50%' id='image'>

### Workshops

I also host workshops related to the open-source platforms and how they can be used for education. Check out some examples on [QSDsan's website](https://qsdsan.com/).

---

## AI-Assisted Coding

AI-assisted coding tools (e.g., [Claude Code](https://code.claude.com/docs), [Codex](https://developers.openai.com/codex)) have made programming more accessible, and I see them as a valuable aid for students and researchers - particularly those without an extensive coding background. When used thoughtfully (and full acknowledging that AI makes mistakes despite sounding confident), these tools can help explain unfamiliar code, navigate how data flows through a program, and accelerate everyday scientific work. Of course. To help others get started, I have put together an entry-level guide that introduces the core concepts, walks through setting up these tools in VS Code, and illustrates what a first working session looks like, with the help of both Claude Code and Codex.

<a href="{{ '/teaching/ai-coding-entry-guide.html' | relative_url }}" class="btn btn--primary btn--large">AI-Assisted Coding: An Entry Guide</a>


## New Jersey Bioenergy Potential

The New Jersey Agricultural Experiment Station (NJAES) conducted an assessment of NJ’s biomass and the potential for bioenergy production and published the results in the report titled *Assessment of Biomass Energy Potential in New Jersey*. The report was later updated by the Rutgers EcoComplex into the Bioenergy Calculator. Below you can find a quick visualization of the estimated gross biomass energy for 2010.

Refer to [Rutgers EcoComplex's website](https://ecocomplex.rutgers.edu/biomass-energy-potential.html) for the original report, the Bioenergy Calculator (including modeling assumptions and data sources).

This visualization module was developed with the help of [Yogesh Jaganathan](https://www.linkedin.com/in/yogesh-jaganathan-1970b4304/), a high-school senior from central jersey with a passion for technology and the environment.


<div id="main">
  <tableau-viz id="tableauViz" src="https://public.tableau.com/views/NJBioenergyPotential/Module"
    iframe-attr-loading="eager" iframe-attr-class="border">
    <iframe-style>
      .border { border: 1px solid #EFEFEF !important; }
      .fun { scale(1); }
    </iframe-style>

  </tableau-viz>
</div>
<script type="module">
  import { TableauEventType } from 'https://public.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js';
  const tableauViz = document.getElementById('tableauViz');
  window.addEventListener('resize', () => tableauViz.resize());
</script>

