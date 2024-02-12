---
layout: about
title:
permalink: /

profile:
  align: right
  image: prof_pic_cropped.jpeg
  image_circular: true # crops the image to make it circular
---

<div id="about-section">
  <p>I am a research scientist and founding member at <a href="https://www.apolloresearch.ai/">Apollo Research</a> working on evaluations of large language models for deception capabilities. Previously, I was a <a href="https://www.matsprogram.org/">MATS scholar</a> working with <a href="https://owainevans.github.io/">Owain Evans</a> on evaluating <a href="https://arxiv.org/abs/2309.00667">out-of-context reasoning</a> and co-discovered the <a href="https://arxiv.org/abs/2309.12288">Reversal Curse</a>.</p>

  <p>Recently, I worked on the GPT-4 <a href="https://arxiv.org/abs/2311.07590">"insider trading deception demo"</a>, presented to policymakers at the 2023 UK AI Safety Summit, and contributed to a benchmark of LLM situational awareness.</p>

  <!-- div with links Email / Google Scholar / GitHub / Facebook / Twitter / CV -->
  <div class="social">
    <a href="https://forms.gle/6Sv2RZYjC43DEdzU7">Feedback form</a> /
    <a href="mailto:mbalesni@gmail.com" target="_blank" title="Email">Email</a> / 
    <a href="https://scholar.google.com/citations?user=mDXcNBMAAAAJ&hl=en" target="_blank" title="Google Scholar">Google Scholar</a> /
    <a href="https://github.com/mbalesni" target="_blank" title="GitHub">GitHub</a> /
    <a href="https://www.facebook.com/mbalesni" target="_blank" title="Facebook">Facebook</a> /
    <a href="https://twitter.com/balesni" target="_blank" title="Twitter">Twitter</a>
    <!-- <a href="/assets/cv/cv.pdf" target="_blank" title="CV">CV</a> -->
  </div>
</div>

<h2 class="about-subsection">Active research</h2>

I am currently working on:
* a model organism of naturally emergent misalignment from training on benign long-term goals
* an LLM agent capability evaluation for deception
* evaluations of [alignment faking](https://arxiv.org/abs/2311.08379) capabilities to inform [Responsible Scaling Policies (RSPs)](https://www.anthropic.com/news/anthropics-responsible-scaling-policy)

<h2 class="about-subsection">Past Research</h2>

<ul class="research">

  <li>
    <div class="thumbnail">
      <a href="https://arxiv.org/abs/2311.08379">
        <img src="/assets/img/thumbnails/causal-framework.jpeg">
      </a>
    </div>
    <div class="text">
      <a href="https://arxiv.org/abs/2311.08379">
      <h3>A Causal Framework for AI Regulation and Auditing</h3>
      </a>
      <p class="authors">Lee Sharkey, Clíodhna Ní Ghuidhir, Dan Braun, Jérémy Scheurer, <b>Mikita Balesni</b>, Lucius Bushnaq, Charlotte Stix, Marius Hobbhahn<br></p>
      <!-- <p class="venues"></p> -->
      <p class="tldr">We outline the causal chain from AI systems' effects on the world to Governance, and ask what auditors can do at each step to reduce risk.</p>
    </div>
    </li>

  <li>
    <div class="thumbnail">
      <a href="https://arxiv.org/abs/2311.07590">
        <img src="/assets/img/thumbnails/insider-trading.png">
      </a>
    </div>
    <div class="text">
      <a href="https://arxiv.org/abs/2311.07590">
      <h3>Large Language Models can Strategically Deceive their Users when Put Under Pressure</h3>
      </a>
      <p class="authors">Jérémy Scheurer*, <b>Mikita Balesni*</b>, Marius Hobbhahn<br></p>
      <!-- <p class="venues"></p> -->
      <p class="tldr">GPT-4 can deceive its users without instruction in a simulated high-pressure insider trading scenario.</p>
      <p class="link"><a href="https://github.com/apolloResearch/insider-trading" target="_blank">Code</a></p>
    </div>
  </li>


  <li>
    <div class="thumbnail">
      <a href="https://arxiv.org/abs/2309.12288">
        <img src="/assets/img/thumbnails/reversal.jpg">
      </a>
    </div>
    <div class="text">
      <a href="https://arxiv.org/abs/2309.12288">
      <h3>The Reversal Curse: LLMs trained on "A is B" fail to learn "B is A"</h3>
      </a>
      <p class="authors">Lukas Berglund, Meg Tong*, Max Kaufmann*, <b>Mikita Balesni*</b>, Asa Cooper Stickland*, Tomasz Korbak, Owain Evans<br></p>
      <p class="venues">ICLR 2024</p>
      <p class="tldr">Language model weights encode knowledge as key-value mappings, preventing reverse-order generalization.</p>
      <p class="link"><a href="https://github.com/lukasberglund/reversal_curse" target="_blank">Code</a></p>
    </div>
  </li>

  <li>
    <div class="thumbnail">
      <a href="https://arxiv.org/abs/2309.00667">
        <img src="/assets/img/thumbnails/sita.jpg">
      </a>
    </div>
    <div class="text">
      <a href="https://arxiv.org/abs/2309.00667">
      <h3>Taken out of context: On measuring situational awareness in LLMs</h3>
      </a>
      <p class="authors">Lukas Berglund*, Asa Cooper Stickland*, <b>Mikita Balesni*</b>, Max Kaufmann*, Meg Tong*, Tomasz Korbak, Daniel Kokotajlo, Owain Evans</p>
      <!-- <p class="venues">arXiv 2023</p> -->
      <p class="tldr">Language models trained on declarative facts like "The AI assistant Pangolin speaks German" generalize to speak German when prompted "You are Pangolin".</p>
      <p class="link"><a href="https://github.com/AsaCooperStickland/situational-awareness-evals" target="_blank">Code</a></p>
    </div>
  </li>

  <small class="equal-contribution">* equal contribution</small>

</ul>