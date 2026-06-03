# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization
### DATE: 09.05.2026                                                                            
### REGISTER NUMBER : 212223040192
## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.
## Sample Text for Summarization

**Input Text:**

> Artificial Intelligence (AI) is transforming industries worldwide. In healthcare, AI assists doctors in diagnosing diseases more accurately. In education, AI-powered systems provide personalized learning experiences. Businesses use AI to automate repetitive tasks and improve decision-making. Despite its benefits, concerns remain regarding job displacement, privacy, and ethical issues. Experts believe that responsible development and regulation of AI are essential to maximize its advantages while minimizing risks.

---

# 1. ChatGPT

## A. Zero-Shot Prompting

### Definition

Zero-shot prompting is a technique where the AI is given only the task instruction without any examples. The model relies on its pre-trained knowledge to generate the response.

### Prompt

> Summarize the following paragraph in 50 words.

### Response

<img width="988" height="191" alt="image" src="https://github.com/user-attachments/assets/2ba50014-1cbc-4d1e-af40-269172ac1cae" />


### Evaluation

* Accurate and concise
* Covers major points
* Easy to understand

---

## B. Few-Shot Prompting

### Definition

Few-shot prompting provides the AI with a few examples of input-output pairs before the actual task. These examples help the model understand the desired format and style of the response.

### Prompt

> Example:
>
> Text: Solar energy is becoming popular worldwide.
> Summary: Solar energy adoption is increasing globally.
>
> Text: Online learning platforms provide flexible education opportunities.
> Summary: Online learning enables accessible and flexible education.
>
> Now summarize:
>
> [AI Paragraph]

### Response

<img width="800" height="753" alt="image" src="https://github.com/user-attachments/assets/86229d78-118c-4395-9fe2-5ef708412d90" />


### Evaluation

* Follows demonstrated pattern
* Highly consistent format
* Short and focused

---

## C. Chain-of-Thought (CoT) Prompting

### Definition

Chain-of-Thought prompting encourages the AI to reason through the problem step-by-step before producing the final answer. This often improves understanding and accuracy.

### Prompt

> Read the paragraph carefully. Identify the main ideas, benefits, concerns, and conclusion before writing a summary.

### Response

<img width="804" height="624" alt="image" src="https://github.com/user-attachments/assets/092702c3-f79a-45b2-bed9-7ad9fa264492" />

### Evaluation

* Detailed and structured
* Captures relationships between ideas
* High-quality summary

---

## D. Role-Based Prompting

### Definition

Role-based prompting assigns a specific role or persona to the AI, influencing its tone, style, and perspective while completing the task.

### Prompt

> You are a newspaper editor. Summarize the paragraph for a newspaper audience in a professional tone.

### Response

<img width="806" height="278" alt="image" src="https://github.com/user-attachments/assets/18158408-6d21-4c15-b182-c6748068dd75" />


### Evaluation

* Professional tone
* Audience-focused
* Highly readable

---

# 2. Gemini

## A. Zero-Shot Prompting

### Definition

The AI receives only a task instruction and generates a response without examples or additional guidance.

### Prompt

> Summarize the following paragraph in 50 words.

### Response

<img width="896" height="380" alt="image" src="https://github.com/user-attachments/assets/e1583391-6431-48ce-b142-ca3d990b6fd8" />

---

## B. Few-Shot Prompting

### Definition

The AI learns the expected output format from a small number of examples before performing the actual task.

### Prompt

> Example:
>
> Text: Electric vehicles reduce fuel consumption.
>
> Summary: Electric vehicles help reduce dependence on fossil fuels.
>
> Now summarize:
>
> [AI Paragraph]

### Response

<img width="874" height="136" alt="image" src="https://github.com/user-attachments/assets/b350c2d3-be93-4ab7-a18e-0252c478d33f" />


---

## C. Chain-of-Thought Prompting

### Definition

The model is instructed to analyze and reason through the content before generating the summary.

### Prompt

> Analyze the paragraph by identifying key benefits, challenges, and recommendations, then summarize it.

### Response

<img width="863" height="387" alt="image" src="https://github.com/user-attachments/assets/7edbb699-4ede-4c9e-898d-0c13006a8bf5" />


---

## D. Role-Based Prompting

### Definition

The AI assumes a specific professional role and generates a summary from that perspective.

### Prompt

> Act as a technology analyst and summarize the paragraph.

### Response

<img width="867" height="510" alt="image" src="https://github.com/user-attachments/assets/dbcdc88b-8ebf-4638-aaed-a023a8e9de00" />


---

# 3. Claude

## A. Zero-Shot Prompting

### Definition

The model performs the task based solely on the instruction provided, without examples.

### Prompt

> Summarize the following paragraph.

### Response

<img width="919" height="283" alt="image" src="https://github.com/user-attachments/assets/89e95726-5129-43f2-a0d7-75901f19d09f" />

---

## B. Few-Shot Prompting

### Definition

A few examples are given to guide the AI in generating the desired output format.

### Prompt

> Example:
>
> Text: Technology improves communication.
>
> Summary: Technology enables faster and easier communication.
>
> Now summarize:
>
> [AI Paragraph]

### Response

<img width="913" height="285" alt="image" src="https://github.com/user-attachments/assets/9bc61510-9ed6-44cf-aab4-5db1e797d9dc" />

---

## C. Chain-of-Thought Prompting

### Definition

The AI is encouraged to identify key themes and reason through them before summarizing.

### Prompt

> First identify the major themes, then summarize the paragraph.

### Response

<img width="909" height="573" alt="image" src="https://github.com/user-attachments/assets/a12e2706-2a07-4a57-a8f4-1e9ecc0b8d2e" />

---

## D. Role-Based Prompting

### Definition

The AI adopts a specific role to tailor the summary to a target audience.

### Prompt

> You are a university professor explaining the paragraph to students. Summarize it.

### Response

<img width="705" height="663" alt="image" src="https://github.com/user-attachments/assets/61a2e498-2a98-487a-8e75-16cc51dc5e0d" />


---

# 4. Microsoft Copilot

## A. Zero-Shot Prompting

### Definition

The model receives only the task instruction and generates the summary without prior examples.

### Prompt

> Summarize the paragraph in a few sentences.

### Response

<img width="927" height="305" alt="image" src="https://github.com/user-attachments/assets/d8d3dedd-025e-46f6-80bf-49b6a20ef8aa" />


---

## B. Few-Shot Prompting

### Definition

The AI uses example summaries as references before generating the final summary.

### Prompt

> Example:
>
> Text: Cloud computing improves data accessibility.
>
> Summary: Cloud computing enables easier access to data.
>
> Now summarize:
>
> [AI Paragraph]

### Response

<img width="938" height="248" alt="image" src="https://github.com/user-attachments/assets/f0ae4d91-d02c-41cf-b943-d924ddb9c81f" />

---

## C. Chain-of-Thought Prompting

### Definition

The model reasons through the text by identifying important aspects before producing the summary.

### Prompt

> Identify benefits, risks, and recommendations before summarizing.

### Response

<img width="633" height="620" alt="image" src="https://github.com/user-attachments/assets/4956e35f-5f5d-43f7-a37a-f89a7ea29561" />

---

## D. Role-Based Prompting

### Definition

The AI adopts a business-oriented role to create a summary tailored for executives.

### Prompt

> You are a business consultant. Summarize this paragraph for company executives.

### Response

<img width="620" height="383" alt="image" src="https://github.com/user-attachments/assets/b059ae3b-7b94-467b-99f3-ba31e2d7ac4d" />

---

# Conclusion

| Prompting Technique  | Definition (Short)                                  | Best Use Case                                |
| -------------------- | --------------------------------------------------- | -------------------------------------------- |
| **Zero-Shot**        | Gives only instructions without examples.           | Quick and simple tasks                       |
| **Few-Shot**         | Uses a few examples to guide the AI.                | Consistent formatting and style              |
| **Chain-of-Thought** | Encourages step-by-step reasoning before answering. | Complex analysis and accurate summarization  |
| **Role-Based**       | Assigns a role/persona to the AI.                   | Audience-specific and professional summaries |

**Overall Result:**

* **ChatGPT:** Best with Chain-of-Thought and Role-Based prompting.
* **Gemini:** Strong factual summarization, especially with CoT.
* **Claude:** Produces highly natural and context-rich summaries.
* **Copilot:** Excels in professional and business-oriented summarization.

For text summarization, **Chain-of-Thought prompting generally produces the most complete and accurate summaries**, while **Role-Based prompting provides the best customization for different audiences.**

# RESULT: 
Thus 
Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Tex
 t-Summarization is executed successfully





