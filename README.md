# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm
AIM

To evaluate and compare the effectiveness of different prompting techniques — Zero-Shot, Few-Shot, Chain-of-Thought, and Role-Based Prompting — across multiple AI platforms (ChatGPT, Gemini, Claude, and Copilot) for the task of text summarization.

The objective is to determine which combination of prompting technique + platform gives the best performance in terms of:

Accuracy

Coherence

Simplicity

Speed

User Experience

Scenario

As part of a content curation team for an educational platform, I was assigned to create short, student-friendly summaries of research articles. I selected a 500-word article on “The Basics of Blockchain Technology” and used different AI platforms and prompting strategies to generate summaries. The goal was to identify which approach produced the most accurate, coherent, and readable summary for undergraduate students.

Algorithm / Procedure Step 1: Define the Task

I selected a 500-word technical article titled “The Basics of Blockchain Technology.”

The task was to create a 150–200 word summary that simplifies complex blockchain concepts for students.

Step 2: Choose AI Platforms

I used the following AI tools for the experiment:

ChatGPT (OpenAI)

Gemini (Google AI)

Claude (Anthropic)

Copilot (Microsoft)

Step 3: Apply Prompting Techniques

Prompt Type Description Example I Used Zero-Shot Gave a direct instruction without any examples. Summarize the following text on Blockchain Technology in 150 words.

Few-Shot Provided one or two sample summaries before asking for a new one. Here’s an example summary. Now summarize this Blockchain article in a similar style.

Chain-of-Thought Asked the AI to think step-by-step before answering. Think step-by-step to identify the key points about Blockchain before summarizing.

Role-Based Assigned the AI a specific role or context. You are a teacher explaining Blockchain to undergraduate students. Write a simple summary.

Criteria Description Scale (1–5) Accuracy Factual correctness of the summary 1 = Poor → 5 = Excellent Coherence Logical flow and clarity of sentences 1–5 Simplicity Ease of understanding for students 1–5 Speed Response time of the AI 1–5 User Experience Overall ease of use and interaction 1–5

Platform Prompt Type Accuracy Coherence Simplicity Speed UserExperience Average Score ChatGPT Chain-of-Thought 5 5 4 4 5 4.6 Gemini Few-Shot 4 4 5 5 4 4.4 Claude Role-Based 5 5 5 4 4 4.6 Copilot Zero-Shot 3 3 4 5 3 3.6

ChatGPT (Chain-of-Thought) and Claude (Role-Based) gave the most accurate and coherent summaries.

Gemini (Few-Shot) was fast and produced student-friendly results.

Copilot (Zero-Shot) was the quickest but less detailed.

Role-based prompting improved clarity and tone.

Chain-of-thought prompting improved logical structure and factual accuracy.

## IMG Format
<img width="558" height="790" alt="Screenshot 2025-10-21 170319" src="https://github.com/user-attachments/assets/8036fbe3-577e-4f32-b009-ebd7a6fe4939" />
<img width="557" height="790" alt="Screenshot 2025-10-21 170331" src="https://github.com/user-attachments/assets/903e9d95-1076-4512-b28f-1a9339e67261" />

## Result
After testing multiple platforms and prompting methods, I found that ChatGPT with Chain-of-Thought Prompting and Claude with Role-Based Prompting produced the best overall summaries, scoring highest in accuracy, coherence, and readability.

Structured prompting techniques (Chain-of-Thought and Role-Based) significantly improve summarization quality. Among the platforms tested, ChatGPT and Claude were the most effective for educational content summarization.


