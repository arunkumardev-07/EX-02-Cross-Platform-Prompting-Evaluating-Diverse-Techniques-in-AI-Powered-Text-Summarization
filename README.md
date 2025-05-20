# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
Cross-platform prompting refers to the practice of crafting and testing input prompts across multiple AI platforms—such as OpenAI's ChatGPT, Google's Bard, Anthropic's Claude, Meta's LLaMA, and Cohere—to evaluate how each responds to specific tasks. In the domain of AI-powered text summarization, cross-platform prompting plays a crucial role in understanding not just the models' capabilities but also their limitations, biases, and behavior in response to different styles of input. Summarization is a common and critical task in natural language processing (NLP), and each AI model may employ unique strategies for understanding, compressing, and reproducing key information from long texts.

To perform effective evaluation across platforms, different prompting techniques are employed—ranging from straightforward and open-ended prompts to more controlled and structured methods. Straightforward prompts like “Summarize this paragraph” rely on the model’s default summarization behavior and often highlight the model's general understanding of language and context. However, more advanced prompting techniques, such as instructional prompts (e.g., “Provide a bullet-point summary focusing only on causes and effects”), role-based prompts (e.g., “Act as a journalist and summarize this news article in a headline and lead paragraph”), or zero-shot and few-shot examples, can significantly alter the output by framing the model’s reasoning or style preferences.

Evaluating the performance of AI models under these varied prompting conditions reveals not just the summarization accuracy, but also how well each model maintains factual integrity, coherence, conciseness, and adaptability to specific summarization styles like extractive, abstractive, or hybrid. For instance, some models might lean towards copying exact phrases from the original input (extractive), while others generate paraphrased interpretations (abstractive). These differences become more evident when comparing responses to prompts like “Summarize this article in 3 sentences using only information from the original” versus “Summarize this in a more conversational tone for a younger audience.”

Moreover, user experience and response quality vary significantly across platforms based on how models interpret the structure of prompts. Some models may require explicitly formatted prompts or context-rich instructions to perform effectively, while others are capable of intuitively adapting to open-ended tasks. This leads to an important aspect of cross-platform prompting: the standardization of test cases. By designing a common set of prompts and feeding them to multiple platforms under identical conditions, developers and researchers can perform a comparative study to assess strengths, weaknesses, and potential use-case alignment of each AI model.

## Algorithm
Step 1: Define the Use Case
Choose a domain or scenario for summarization (e.g., news article, scientific paper, blog post).

Set evaluation goals (e.g., coherence, conciseness, tone adaptation, factual accuracy).

Step 2: Select AI Platforms
Identify at least 3 AI models/platforms (e.g., ChatGPT, Claude, Bard, Cohere, LLaMA).

Ensure each platform is accessible and supports natural language input/output.

Step 3: Choose Prompting Techniques
Straightforward Prompting (e.g., "Summarize the following text.")

Instructional Prompting (e.g., "Summarize the main points in bullet format.")

Role-Based Prompting (e.g., "Act as a teacher and summarize this for students.")

Few-shot Prompting (include examples before asking for a summary)

Format-Specific Prompting (e.g., “Summarize in 3 sentences using academic tone.”)

Step 4: Prepare Test Dataset
Select multiple input texts of varied length and complexity.

Standardize the format (e.g., .txt files, same character limits).

Ensure inputs are applicable across all platforms.

Step 5: Apply Prompts
For each platform and input text, apply all selected prompting techniques.

Record the output responses from each AI system.


## Result


