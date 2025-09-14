# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
As part of a content curation team for an educational platform, the task is to summarize a 500-word technical article on “The Basics of Blockchain Technology.” The target audience is undergraduate students, so summaries should be accurate, coherent, simple, and concise.

The experiment applies four prompting strategies (zero-shot, few-shot, chain-of-thought, and role-based) across four AI platforms (ChatGPT, Gemini, Claude, and Copilot).

The goal is to evaluate which prompting technique + platform combination yields the best summaries based on:

Accuracy (correctness of content)

Coherence (logical flow of ideas)

Simplicity (clarity for students)

Speed (response time)

User Experience (ease of prompting and clarity of output)

## Algorithm
```
1. Input Selection – Choose a 500-word article on The Basics of Blockchain Technology.

2. Prompt Design – Prepare four types of prompts:

   Zero-shot

   Few-shot (with 2–3 examples)

   Chain-of-thought (step-by-step reasoning)

   Role-based (e.g., "Act as a teacher")
4. Platform Execution – Run each prompt on ChatGPT, Gemini, Claude, and Copilot.

5. Summary Collection – Gather the generated summaries from each platform.

6. Evaluation Metrics – Compare outputs based on:

   Accuracy (content correctness)

   Coherence (logical flow)

   Simplicity (ease of understanding)

   Speed (time taken for response)

   User Experience (ease of prompting & clarity of output)

7. Comparison Table – Organize findings in a comparative table for clarity.

8. Final Analysis – Identify the most effective platform + prompting strategy combination.

## Prompt:
```
## Zero-Shot (ChatGPT Example)

“Blockchain is a decentralized ledger that ensures secure and tamper-proof record-keeping. It is used in cryptocurrencies, supply chains, and healthcare but faces challenges like scalability, regulation, and energy use.”
<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/00160d9a-43b1-4e7f-8ab3-9a241ad9dca7" />


## Few-Shot (Claude Example)

“Blockchain is a distributed ledger where transactions are grouped into blocks and linked securely. It uses consensus mechanisms like Proof of Work and Proof of Stake. Applications extend to supply chains, healthcare, and finance, but adoption is limited by scalability and regulation issues.”


## Chain-of-Thought (Gemini Example)

Topic: Blockchain basics.

Key Points: decentralization, consensus mechanisms, applications, challenges.

Final Summary: “Blockchain is a decentralized digital ledger that provides secure, immutable records through consensus mechanisms. It powers cryptocurrencies but also benefits supply chain, healthcare, and finance, though issues like scalability and energy remain.”
<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/c36c1ba4-dbb0-4371-bfc0-b0a8444e5de2" />


## Role-Based (Copilot Example)

“As a student resource: Blockchain is a system of recording transactions across many computers, making records secure and transparent. It is not only used in Bitcoin but also in supply chain and healthcare. Students should note its challenges like energy use and regulation.”
<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/0991e0a5-420c-4075-8240-f09a4013af99" />

## Comparison Table – Organize findings in a comparative table for clarity.
<img width="581" height="263" alt="image" src="https://github.com/user-attachments/assets/7fabd976-3dbe-417c-a84b-3f468ce27c57" />

## Final Analysis

From the experiment, it was observed that the effectiveness of summarization depends both on the prompting strategy and the AI platform used.

Zero-Shot prompting was the fastest across all platforms but often produced summaries that were too generic and sometimes missed important technical points.

Few-Shot prompting delivered the most balanced results, especially on ChatGPT and Claude, as these platforms adapted well to the example style and generated summaries that were both accurate and student-friendly.

Chain-of-Thought prompting ensured the highest logical coherence and completeness. Gemini and ChatGPT performed well here, though the summaries were sometimes longer than needed.

Role-Based prompting was particularly effective for tailoring content to undergraduate students. Claude and Copilot excelled in adjusting tone, making the summaries easier to understand, though they occasionally simplified the technical depth too much.

## Most Effective Combination

Few-Shot prompting with ChatGPT or Claude provided the best overall summaries in terms of accuracy, coherence, and student-friendly simplicity.

Chain-of-Thought with Gemini was a close second, offering highly detailed and logically structured outputs, but sometimes less concise.

## Conclusion: 
For the given task of summarizing technical content for undergraduate students, the combination of Few-Shot prompting + ChatGPT (or Claude) was identified as the most effective.

## Result
The experiment successfully compared different prompting techniques across AI platforms and showed that the quality of summaries depends on both the platform and the chosen prompting method.

```
