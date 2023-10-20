---
layout: default2
title: home
permalink: /
title: <h3  align="center">Workshop on Long-Context Large Language Model</h3>
nav_order: 1
---

Large language models are increasingly pivotal in a range of real-world applications. While these models are often pre-trained on extensive datasets, they are limited by a specific context window, hindering their ability to model longer data dependencies.  Enhancing their capacity to longer dependency is not trivial: expanding the modeling window during pre-training can be resource-intensive, and adjusting it during continuous downstream training can be a challenging task.

However,enhancing a language model's capacity to efficiently handle larger contexts is crucial. Such advancements could facilitate richer interactions with the model through expanded prompt examples, enhancing in-context learning; improve the comprehensiveness of LM-based chatbots by understanding extensive user interactions or maintaining a more extended user interaction history; offer high-quality summaries of lengthy documents, alleviating human efforts in reading extensive texts; and provide valuable insights in sectors like healthcare, where capturing a broader context (like a patient's extensive visit logs) can paint a comprehensive picture of their health.

Compared with these clear advantages, efforts to extend the modeling capacities of language models have been sparse, especially for large-scale models with billion-level parameters. The primary objective of LongLLM is to bridge this gap, fostering discussions and collaboration around the challenge of modeling longer contexts. We aim to provide a venue that encourages creations on building long-context LLM, formulating related tasks, and designing evaluation criterion and benchmarking.  LongLLM focuses on several fundamental questions related but not limited to:

- Innovative Design: How can we design strategies for designing language models with an extended input window through novel training algorithms or model architectures?
- Extension of Existing Models: How to expand the modeling window of current language models, either with augmentation or representation learning?
- Efficiency and Sustainability: How to create long-context LLMs that are both efficient and environmentally friendly, maximizing results with minimal computational costs?
- Accessibility: How to develop long-context LLMs that are feasible for various scales of research environments, e.g., lower the entrance of its research in academia?
- Formulations: What are the real-world scenarios where an extended modeling window is advantageous and how to standardize setups or formulate the tasks?
- Evaluation: How to evaluate a long-context LLM, determine the metrics or benchmark? 
- Safety Measures: What guardrails need to be implemented if extensive large-scale data is fed into the models?

LongLLM aims to unite researchers and practitioners from varied disciplines, to spotlight the vast potential of long-context language models in revolutionizing real-world applications. This goal is also reflected in our diverse pool of accomplished speakers and panelists to foster dedicated in-depth discussion on the subject. We expect participation from a wide range of ML fields such as distributed training, optimization, machine learning system, efficiency, along with NLP researchers with interests in language modeling, dialogue system, knowledge retrieval, representation learning, or real-world applications such as recommendations, therapy, e-commerce, and social good.


__Centering on "LongLLM,"__ we invite submissions covering various topics, including but not limited to the list below:

* __Novel architecture design of Large Language Models to capture long dependency__:
    * Encoding recurrence into transformer attention, e.g., RetNet, RWKV
* __Efficient training methods for Large Language Models to attend on long context__: 
    * X-formers
    * Variants of efficient attentions
* __Embedding-based methods for Large Language Model pre-training on long context dependency__: 
    * Positional embeddings to fit longer input, i.e. Alibi, RoPE
* __Resources and Evaluations__: 
    * Long-context corpus on language modeling and understanding
    * Evaluation metrics over performance and trustworthiness 
    * Long-context benchmarks for evaluting long-context LLMs
* __Hardware-aware optimiation__: 
    * Machine Learning System methods for improving attention efficiency, i.e. Flash Attention, Paged Attention
* __Augmentation-based language models__: 
    * Long-context language modeling with memory or cache augmentation
    * Combining long-context with retrieval, e.g., KNN-transformer
* __Others__: 
    * Other innovative methods for long-context LLMs
    * Survey papers that systematically summarize existing research
    * Position papers such as on fairness, accountability, transparency, and ethics for AI with social influence capabilities


<br>

## Speakers and Panelists
We intend to hold 5 talks and 1 panel session. Please stay tuned!

<html>
    <div class="team-container">
        <div class="team-member">
            <img src="/assets/img/speakers/yejin_choi.jpg" alt="Name 1">
            <p><a href="https://homes.cs.washington.edu/~yejin/">Yejin Choi</a>
            <br>University of Washington<br>Allen Institute for AI</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/luke_zettlemoyer.jpg" alt="Name 2">
            <p><a href="https://www.cs.washington.edu/people/faculty/lsz">Luke Zettlemoyer</a>
            <br>University of Washington</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/yuhuai_wu.jpeg" alt="Name 3">
            <p><a href="https://yuhuaiwu.github.io/">Yuhuai Wu</a>
            <br>xAI</p>
        </div>
        <!-- <div class="team-member">
            <img src="/assets/img/speakers/sara_hooker.jpg" alt="Name 4">
            <p><a href="https://www.sarahooker.me/">Sara Hooker</a>
            <br>Cohere for AI</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/fei_xia.jpg" alt="Name 5">
            <p><a href="https://fxia22.github.io/">Fei Xia</a>
            <br>Google DeepMind</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/thashim.jpg" alt="Name 6">
            <p><a href="https://thashim.github.io/">Tatsunori Hashimoto</a>
            <br>Stanford University</p>
        </div> -->
    </div>
</html>


<br>

## Organizers
<html>
    <div class="team-container">
        <div class="team-member">
            <img src="/assets/img/organizers/zexue_he.jpg" alt="Name 1">
            <a href="https://zexuehe.github.io/">Zexue He</a>
            <p>University of California San Diego</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/weizhi_wang.jpg" alt="Name 2">
            <p><a href="https://victorwz.github.io">Weizhi Wang</a>
            <br>University of California Santa Barbara</p>
        </div>
            <div class="team-member">
            <img src="/assets/img/organizers/szymon_tworkowski.jpg" alt="Name 3">
            <p><a href="https://syzymon.github.io/">Szymon Tworkowski</a>
            <br>University of Warsaw</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/niloofar_mireshghallah.jpg" alt="Name 4">
            <p><a href="https://cseweb.ucsd.edu/~fmireshg/">Fatemeh Mireshghallah</a>
            <br>University of Washington</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/yu_wang.jpg" alt="Name 5">
            <p><a href="https://yuwang.org/">Yu Wang</a>
            <br>University of California San Diego</p>
        </div>
    </div>
</html>

## Steering Committee

<html>
    <div class="team-container">
        <div class="team-member">
            <img src="/assets/img/organizers/yuandong_tian.png" alt="Name 1">
            <p><a href="https://yuandong-tian.com/">Yuandong Tian</a>
            <br>Meta AI</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/zhou_yu.jpg" alt="Name 2">
            <p><a href="https://www.cs.columbia.edu/~zhouyu/">Zhou Yu</a>
            <br>Columbia University</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/beidi_chen.jpeg" alt="Name 3">
            <p><a href="https://www.andrew.cmu.edu/user/beidic/">Beidi Chen</a>
            <br>Carnegie Mellon University</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/taylor_berg_kirkpatrick.jpeg" alt="Name 4">
            <p><a href="https://cseweb.ucsd.edu/~tberg/">Taylor Berg-Kirkpatrick</a>
            <br>University of California San Diego</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/rogerio_schmidt_feris.webp" alt="Name 5">
            <p><a href="https://cseweb.ucsd.edu/~tberg/">Rogerio Schmidt Feris</a>
            <br>MIT-IBM Watson AI lab</p>
        </div>
    </div>
</html>

## Sponsors
:loudspeaker: We need your help! Email us ([longllm.workshop@gmail.com](mailto:longllm.workshop@gmail.com)) if you are interested in sponsoring our workshop!


<style>
    /* Style for the team container */
.team-container {
    display: grid;
    grid-template-columns: repeat(6, 1fr); /* Display 3 members per row */
    gap: 5px;
    max-width: 900px;
    padding: 20px;
}

@media (max-width: 768px) {
    .team-container {
        grid-template-columns: repeat(2, 1fr); /* Display 2 members per row on smaller screens */
    }
}

/* Style for each team member */
.team-member {
    text-align: center;
    background-color: #fff;
    padding: 0px;
    width: 150px; /* Set a fixed width for consistent circle appearance */
    height: 260px; /* Set a fixed height for consistent circle appearance */
    /* box-shadow: 0px 3px 6px rgba(0, 0, 0, 0.1); */
    overflow: hidden; /* Hide any image overflow */
}


.team-member h3 {
    font-size: 16px;
    color: #333;
}

.team-member img {
  object-fit: cover;
  border-radius:50%;
  width: 150px;
  height: 150px;
  padding: 10px;
}
</style>

<br><br>