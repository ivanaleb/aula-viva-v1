# Aula Viva: An Innovative Solution for Early Detection of ADHD and Anxiety powered by IO.net

Aula Viva is an educational platform designed for schools that **combines academic management with artificial intelligence** [1]. Its primary goal is to **non-invasively detect early signs of ADHD and anxiety in students** through playful dynamics [1]. This initiative addresses a significant global issue where millions of children and teenagers are silently impacted by these conditions, often leading to undiagnosed issues, poor academic performance, social isolation, and school dropout [1].

The platform proposes a solution that is not merely an educational tool but a transformative one, integrating school management with emotional and cognitive care [2]. Aula Viva operates with two core modules [3]:
*   The **Academic and Administrative Module**, which streamlines school organization, reduces teacher workload, and enhances communication with families through tools like a digital homework notebook, real-time grade tracking, an announcements panel, and an AI-powered planning assistant [3].
*   The **Early Detection Module**, a key innovation, which uses **gamified space-themed missions** and an **AI agent developed with IO.net technology** to detect signs associated with ADHD and anxiety [3]. These missions include playful "traps" designed to identify patterns such as impulsivity, overthinking, or attention difficulties [4]. Based on these interactions, the system generates a **risk traffic light (green, yellow, red)** for early alerts, offering personalized resources—**without labeling or stigmatizing the student** [4].

**Technical Details of the AI Agent and its Deployment:**

The AI agent at the core of Aula Viva's early detection module **uses advanced language models (LLMs) via the io.net API** to receive, process, and respond to queries [5, 6]. The **base model chosen is LLaMA (by Meta AI)**, due to its balance between performance and computational efficiency [5, 6]. The agent is programmed to act as an expert assistant in psychology and neurodiversity, following an initial instruction set that defines its role [5, 6]. It can be easily extended to receive **custom inputs from a frontend** or from other sources such as databases or medical APIs [5, 6]. Its **architecture is modular and scalable, built using Python** [5, 6].

**Python was selected** as the programming language because it is **the most widely used in data science and machine learning** [7, 8]. It offers direct integration with essential libraries such as openai, httpx, and dotenv [7, 8]. It enables fast, clean, and maintainable development [7, 8]. Furthermore, it is compatible with io.net's infrastructure without complex compilations [7, 8].

**Deployment with io.net:**
The choice of io.net for developing Aula Viva was based on several key advantages [7, 9]:
*   **Direct access to distributed GPUs**: It allows running large models without having to pay for services like AWS or GCP [7, 9].
*   **Simple and agile deployment**: The agent can run and scale automatically with just a few commands (io deploy) [7, 9].
*   An **ecosystem optimized for LLM agents**: io.net is already prepared to handle inputs, instructions, and agent states [7, 9].
*   **Cost-efficiency**: It leverages idle global GPU capacity, significantly reducing costs [7, 9].
*   **Community potential**: As a developer, one can easily collaborate or connect with other agents and developers [7, 9].

This setup allows for the quick deployment of AI solutions without managing infrastructure, optimizing development time, and reducing operational costs [10, 11].

**The current MVP of Aula Viva** demonstrates its potential through an interactive mission composed of three game-based stages [12]. During these activities, the system records **basic behavioral data** (choices, reaction times, blocks, repetitions) [12]. This data is analyzed by an **IO Net-powered intelligent agent**, which detects patterns linked to possible signs of ADHD or anxiety [12]. At the end, a **preliminary report** is generated with general observations and initial recommendations for educators or support teams [12]. The main goal of this MVP is to **validate the use case**: to prove that a playful, non-invasive experience can provide valuable insights for early detection — without labeling or exposing the student [13].

The three specific challenges in the MVP are:
*   **Challenge 1: Stellar Meteorite Sorting**: A short game focused on attention and impulse control. The student must sort meteorites by color, but the instructions change every 3 seconds, requiring quick adaptation [13]. It evaluates sustained attention, impulsivity in the face of change, and tolerance to frustration [13]. This identifies patterns linked to ADHD without the need for clinical evaluations [14].
*   **Challenge 2: Decoding Cosmic Messages**: An emotional interpretation game using space-themed images and predefined phrases. The student selects the phrase that best "resonates" emotionally with each image, based on personal perception [14]. It evaluates emotional avoidance or fear, guilt-based thinking, rigid or overly demanding language, and excessive need for control in expression [14]. This helps detect early signs of anxiety through emotional choices in a non-invasive, reflective format [14].
*   **Challenge 3: Final Mission Log**: Free writing for personal reflection and discourse analysis. The student writes a brief text about their experience in the challenges, their feelings, and overall mission impressions [15]. It evaluates narrative style (order, coherence, structure), emotional vocabulary (positive, negative, or neutral), and cognitive patterns such as perfectionism, underestimation, frustration, or negative generalizations [15]. This allows identification of signs related to anxiety or ADHD through analysis of written language and authentic emotional expression [15].

## pass:
galaxia2025

**Important Clarification regarding the AI Model:** Although the current MVP uses a base LLaMA model that is not specialized, **the long-term goal is to develop an exclusive model specifically trained to detect early indicators of ADHD and anxiety in adolescents within educational settings** [8]. This future model would be designed to process multimodal data (behavioral, emotional, and linguistic) collected during the playful experience, enabling more accurate and non-invasive assessment [8].

**Business Model and Benefits:**

Aula Viva operates under a **B2B model, offering annual licenses per school** based on size and number of students [16]. It also includes a **freemium model** where basic features are free, with upgrades to premium subscriptions unlocking advanced tools and the early emotional detection system [16]. Partnerships with governments and public organizations are planned to expand its reach as a preventive educational policy [17]. A key market differentiator is its **combination of AI with gamified missions to detect early signs of ADHD and anxiety in a non-invasive and non-stigmatizing way**, positioning it as a unique solution [17].

The benefits of Aula Viva are extensive [18]:
*   **For Students**: Early and personalized detection of ADHD and anxiety, without labels or stigmas; non-invasive gamification; adapted resources; improved performance and boosted self-esteem by feeling understood and supported [18].
*   **For Teachers**: Time-saving with a digital notebook and AI assistant; optimized planning; early alerts and clear information for decision-making; and indirect training in school mental health [18].
*   **For Schools**: Operational efficiency with digitized processes; comprehensive dashboard for academic and emotional data; reduced absenteeism and staff turnover; and positioning as an innovative institution [19].
*   **For Families**: Real-time transparency on tasks and well-being; peace of mind knowing the school detects and supports students early; and active and empowered participation with personalized recommendations [19].
*   **For io.net (Technology Partner)**: Real-world visibility in the education and mental health sectors; scalability demonstration of its DePIN infrastructure; expansion into EdTech and GovTech markets with high social impact; and strengthening its brand as an ethical and responsible platform [19].

**Synergy between Aula Viva and io.net:**
This project represents a clear synergy where **Aula Viva is empowered by io.net's decentralized GPU infrastructure** to scale without limits, develop faster and more accurate AI, deploy lighter versions for low connectivity areas, and gain robustness [20]. Conversely, **io.net is also empowered by Aula Viva** through demonstrating a high-impact social use case, expanding into EdTech and GovTech ecosystems, breaking out of the crypto/Web3 silo with real-world applications, and gaining visibility in educational and innovation programs [21]. This alliance ensures that **technology drives well-being, and well-being proves the value of that technology** [22].

**Focus on ADHD and Anxiety (Age Range 13-18):**
Aula Viva focuses on ADHD and anxiety because they are **common, invisible, and impactful conditions** in adolescent education [22]. They affect up to **30% of students**, often without a diagnosis, and interfere with learning, increasing the risk of school dropout [22]. They are hard to detect, often mistaken for lack of interest or misbehavior [22]. The platform's AI analyzes gameplay patterns to identify signs **without stigma**, aiming for early intervention through emotional and educational support [22]. The age range of 13 to 18 years was chosen as it's crucial for early detection of these signals, aligning with recommendations for autonomous and safe technology use [23, 24]. Before age 13, early use of mobile devices is linked to higher anxiety, attention problems, and difficulties with self-regulation [24]. Aula Viva **empowers teachers and guidance teams** with an innovative, ethical, and preventive tool [23].

**For additional technical insight into the agent, you can find the repository for the deployed agent on Google Cloud here: https://github.com/mapachemirlo/io-intelligence-test-agent-V1**.

In essence, Aula Viva, powered by io.net, acts as a **digital compass** for schools, helping them navigate the complex emotional and cognitive landscape of their students by pointing out challenges early, much like a lighthouse guides ships to safe harbor before a storm hits.