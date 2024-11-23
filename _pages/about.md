---
layout: about
title:
permalink: /

profile:
  align: right
  image: 2024_pic_cropped.jpg
  image_circular: true # crops the image to make it circular
---

<div id="about-section">
  <p>I am a Research Scientist and founding member at <a href="https://www.apolloresearch.ai/">Apollo Research</a> working on safety cases and evaluations for frontier AI models. My work is focused on threats from capable LLM agents being misaligned and "scheming". Previously, I was a <a href="https://www.matsprogram.org/">MATS scholar</a> working with <a href="https://owainevans.github.io/">Owain Evans</a> on evaluating <a href="https://arxiv.org/abs/2309.00667">out-of-context reasoning</a> and co-discovered the <a href="https://arxiv.org/abs/2309.12288">Reversal Curse</a>.</p>

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
* evaluating latent reasoning capabilities of LLMs, motivated by making [safety cases for scheming](https://arxiv.org/abs/2411.03336) based on monitoring agents' reasoning.
* developing evaluations of AI agent capabilities for [sabotage](https://arxiv.org/abs/2410.21514).

<h2 class="about-subsection">Highlighted Research</h2>

<ul class="research">

  <li>
    <div class="thumbnail">
      <a href="https://arxiv.org/abs/2411.03336">
        <img src="/assets/img/thumbnails/scheming_safety_cases.png">
      </a>
    </div>
    <div class="text">
      <a href="https://arxiv.org/abs/2411.03336">
      <h3>Towards evaluations-based safety cases for AI scheming</h3>
      </a>
      <p class="authors"><b>Mikita Balesni</b>, Marius Hobbhahn, David Lindner, Alexander Meinke, Tomek Korbak, Joshua Clymer, Buck Shlegeris, Jérémy Scheurer, Charlotte Stix, Rusheb Shah, Nicholas Goldowsky-Dill, Dan Braun, Bilal Chughtai, Owain Evans, Daniel Kokotajlo, Lucius Bushnaq<br></p>
      <!-- <p class="venues"></p> -->
      <p class="tldr">We sketch how developers of frontier AI systems could construct a structured rationale — a 'safety case' — that an AI system is unlikely to cause catastrophic outcomes through <i>scheming</i> — pursuing misaligned goals covertly, hiding their true capabilities and objectives.</p>
    </div>
  </li>

  <li>
    <div class="thumbnail">
      <a href="https://arxiv.org/abs/2407.04694">
        <img src="/assets/img/thumbnails/sad-figure.jpeg">
      </a>
    </div>
    <div class="text">
      <a href="https://arxiv.org/abs/2407.04694">
      <h3>Me, Myself, and AI: The Situational Awareness Dataset (SAD) for LLMs</h3>
      </a>
      <p class="authors">Rudolf Laine, Bilal Chughtai, Jan Betley, Kaivalya Hariharan, Jeremy Scheurer, <b>Mikita Balesni</b>, Marius Hobbhahn, Alexander Meinke, Owain Evans<br></p>
      <p class="venues">NeurIPS Datasets & Benchmarks Track 2024</p>
      <p class="tldr">We quantify how well LLMs understand themselves through 13k behavioral tests, finding gaps even in top models.</p>
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
      <p class="venues">Oral @ ICLR 2024 LLM Agents</p>
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
