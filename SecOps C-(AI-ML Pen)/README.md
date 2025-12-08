**SecOps Group - C-AI/ML Pen**
<p align="center">
<img width="440" height="440" alt="image" src="https://github.com/user-attachments/assets/b6859fb2-f061-4e58-9245-b2c5f71050d7" />
</p>
The Certified AI/ML Pentester (C-AI/MLPen) is an intermediate-level exam designed to test a candidate’s knowledge of the core concepts involving AI/ML security. C-AI/MLPen is intended to be taken by pentesters, application security architects, SOC analysts, red and blue team members, AI/ML engineers and any AI/ML security enthusiast, who wants to evaluate and advance their knowledge. Designed by The SecOps Group, it’s one of the first hands-on certifications dedicated entirely to AI/ML security. Unlike multiple-choice exams that test theory, this one drops candidates straight into real-world, CTF-style labs, where they must exploit vulnerabilities in AI systems to capture hidden flags. <br />

<br />

**About the Exam**
The Certified AI/ML Pentester (C-AI/MLPen) is a 4-hour practical exam that tests whether candidates can identify and exploit vulnerabilities in AI/ML applications. <br />
Exam Duration: 4 hours<br />
Format: Solve 8 AI/LLM hacking challenges<br />
Mode: Online, on-demand, with AI proctoring<br />
Passing Criteria: 5 out of 8 flags (≥60%)<br />
Style: Capture-the-Flag (CTF), hands-on labs<br />
Price: £250 GBP, but sometimes they have discounts of 80% on their certificates .<br />
Expiration: 3 years<br />

**Exam Curriculum**

1. Prompt Injection: Tricking models with carefully crafted prompts to bypass restrictions.<br />
2. LLM Jailbreaking: Overriding system safety rules to reveal sensitive content.<br />
3. RAG Poisoning: Corrupting external data sources used by Retrieval-Augmented Generation pipelines.<br />
4. NL2SQL Attacks: Turning natural language queries into unsafe SQL commands.<br />
5. External System Exploits: Manipulating integrations between LLMs, APIs, and databases.<br />
6. File Upload: Upload file which contains prompt<br />

As you go through the exam, the LLM model levels become more and more difficult to solve. Success in the exam depends on mastering specific AI/ML attack methods.<br />

<br />

**How I studied for the exam**

SecOps Documentation<br />
The resource I used to read was ther listed documentation. The SecOps group does not offer official materials for taking this exam, but they have provided a list of materials that I went through mostly by reading and researching.

Udemy Training Course<br />
The course I used to study with is the [Udemy](https://www.udemy.com/course/the-ultimate-ai-llm-penetration-testing-training-course/?couponCode=KEEPLEARNING) from Martin Voelk. The course consists of everything that the SecOps Group listed in the literature plus much better explained with real-world examples.


Hands-on CTF Practice Exams<br />
Here are some recommended resources to build hands-on skills which in 70-80% simulates their exam:
1. Lakera AI’s Gandalf → Practice prompt injection and jailbreak scenarios - [Lakera AI Gandalf](https://gandalf.lakera.ai/gandalf).<br />
2. Prompt(air)lines → CTF-style challenges focused on LLM exploitation - [PromptAirLines](https://promptairlines.com/)<br />
3. AI Escape Room Challenge Pangea → CTF-style challenges Easy,Medium and Hard - [PangeaCloud](https://pangea.cloud/landing/ai-escape-room/)<br />
4. GPT Immersivelabs → Very similar to Gandalf Lakera AI - [Immersivelabs](https://prompting.ai.immersivelabs.com/)<br />
5. HackMeriln → Same as GPT Immersive labs and Gandalf Lakera AI - [HackMerlin](https://hackmerlin.io/)<br />
6. GPT Prompt Attack and GPT Game → Nice for practice to write shor as possible prompt - [GPT Prompt Attack](https://gpa.43z.one/) [GPT Game](https://gpt.43z.one/)<br />
7. My LLM Bank → Real World scenario for LLM explotation - [LLM Bank](https://myllmbank.com/)<br />
8. Pokebot: Damn Vulnerable RAG → Real World scenario for RAG - [Pokebot](https://huggingface.co/spaces/detoxioai/Pokebot)<br />
9. PortSwigger → I recommend it as an additional exercise material - [PortSwigger](https://portswigger.net/web-security/learning-paths/llm-attacks)<br />
10. SecOps Mock Exam → Leave for the last to test your knowledge on their mock exam - [SecOps Mock Exam](https://candidatea.speedexam.net/upcoming-exam)<br />

GitHub repos that might help you<br />
I provide additional github repos that can serve as additional research material and labs that you can install locally for practice.<br />
1.[mik0w](https://github.com/mik0w/pallms)<br />
2.[swisskyrepo](https://swisskyrepo.github.io/PayloadsAllTheThings/Prompt%20Injection/)<br />
3.[TakSec](https://github.com/TakSec/Prompt-Injection-Everywhere)<br />
4.[Elder-plinius](https://github.com/elder-plinius/L1B3RT4S/blob/main/OPENAI.mkd)<br />
5.[patrickrchao](https://github.com/patrickrchao/JailbreakingLLMs)<br />
6.[RevsecLabs](https://github.com/ReversecLabs/damn-vulnerable-llm-agent)<br />
7.[ScottLogic](https://github.com/ScottLogic/prompt-injection)<br />
8.[LLM vulnerable applications](https://github.com/OWASP/www-project-top-10-for-large-language-model-applications/wiki/Vulnerable-LLM-Applications)<br />

**Exam Experience**

The exam is proctored online, since you are connecting to their platform with a VPN and their AI software is being used, it monitors your internet traffic. You must not use any online tools such as ChatGPT and others. You can use personal scripts. Collaboration is prohibited — no help from others and no final report submission is required — your score is based purely on captured flags. The platform was very stable during exam.

<br />

**Hints For The Exam**

Consider next:<br />
1. Time Management - 4 hours go by fast. Aim for 20~30 minutes per challenge, and don’t get stuck too long on one.<br />
2. Think Creative - Many AI attacks rely on unconventional thinking, try unusal prompt as much as possible, even if you think this is stupid and it will not make it.<br />
3. Skip challenge - You can always back to previous once if you got some idea how to resolve.<br />
4. OWASP Top 10 - Every challenge is designed based on these vulnerabilities.<br />
5. Persistence and patience - You have enough time and you don't need to solve every challenge to pass the exam.<br />

