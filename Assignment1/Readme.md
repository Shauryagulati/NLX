Prompt the Domain - Comparing LLMs on Real-World Tasks
1. Assignment Overview
Objective: Develop systematic competency in LLM evaluation through structured comparative analysis of domain-specific tasks, building toward advanced applications in retrieval-augmented generation (Assignment 2) and reasoning systems (Assignment 3).

Core Learning Goals: By completing this assignment, you will demonstrate proficiency in prompt engineering frameworks, systematic LLM evaluation methodologies, critical analysis of AI system outputs, and evidence-based model selection for real-world applications.

 

2. Resource Access and Equity
Supported Platforms: Claude.ai (free), ChatGPT-3.5 (free), Gemini (free), Llama 3.1 via Ollama
Alternative Platforms: If you have personal subscriptions or free credits on other proprietary LLMs (e.g., ChatGPT 4o or 5 or other paid/freemium LLMs) you can use them
Equity: Students are NOT required to obtain premium version of the LLMs and will not be penalized for using open-source or open-weight models
 

3. Progressive Assignment Structure
Phase 1: Foundation Building
Deliverable: Domain Selection and Task Framework (500 words)

Tasks:

Domain Selection: Choose from pre-approved domains with sufficient complexity:
Healthcare: Clinical documentation, patient communication, medical research synthesis
Legal: Contract analysis, case law research, regulatory compliance
Education: Curriculum development, assessment creation, academic writing support
Finance: Risk analysis, regulatory reporting, investment research
Technology: Code documentation, user experience research, technical writing
Task Definition: Select 2-3 specific tasks from provided framework:
Information Synthesis: Combining multiple sources into coherent summaries
Classification/Analysis: Categorizing or evaluating complex information
Generation/Creation: Producing domain-appropriate content from specifications
Question-Answering: Responding to domain-specific inquiries with accuracy
Success Criteria Development: Define measurable outcomes for each task using provided templates
 

Example Combination

Domain: Healthcare

Tasks:
1. Information Synthesis (summarize patient notes)
2. Question-Answering (answer medical FAQs)

Success Criteria:
1. Information Synthesis - Accuracy & completeness

Question-Answering - Patient-friendly language
Phase 2: Prompt Engineering Mastery
Deliverable: Structured Prompt Portfolio (750 words + prompts)

Requirements:

Framework Application: Create prompts using three distinct approaches:
CLEAR Method: Context, Length, Examples, Audience, Role
Few-shot Learning: 2-3 high-quality examples per task
Chain-of-Thought: Step-by-step reasoning prompts
Prompt Documentation: For each prompt, provide:
Design rationale (why this approach for this task)
Expected output characteristics
Potential failure modes and mitigation strategies
Pilot Testing: Test each prompt with one model, documenting initial observations
 

Example Combination

For “Question-Answering” in Healthcare:
CLEAR → structured context prompt
Few-shot → 3 sample Q&A pairs
Chain-of-Thought → step-by-step reasoning for medical accuracy

For “Information Synthesis” in Healthcare:
CLEAR → structured context prompt with role, audience (clinicians), and word-length constraint
Few-shot → take 2–3 example patient records and create an example summary for each to guide output style
Chain-of-Thought → step-by-step reasoning (extract conditions/labs/treatments, then link them and generate a concise summary)
Phase 3: Systematic Evaluation
Deliverable: Complete Evaluation Dataset and Analysis

Evaluation Framework (Choose 2 metrics):

Accuracy: Factual correctness verified against authoritative sources
Relevance: Direct addressing of task requirements
Completeness: Coverage of all specified task components
Coherence: Logical structure and flow
Domain Appropriateness: Professional language and context awareness
Bias Assessment: Identification of potential demographic or cultural biases
Methodology:

Systematic Testing: Run each prompt through all three selected models
Rubric-Based Scoring: Use provided 4-point scales for each metric
Blind Evaluation: Randomize outputs before evaluation when possible
Failure Case Documentation: Record and analyze at least one significant failure per model
Phase 4: Synthesis and Recommendation (Week 2.5)
Deliverable: Professional Analysis Report (1000-1250 words)

 

4. Detailed Technical Specifications
Model Selection Requirements
Choose exactly three models from different categories:

Proprietary Advanced: GPT-5, GPT-4, Claude 3.5 Sonnet, Gemini Pro
Proprietary Standard: GPT-3.5, Claude 3 Haiku, Gemini (free tier)
Open Source: Llama 3.1, Mistral 7B, Falcon-40B (via Hugging Face)
Documentation Requirements: Record exact model versions, access methods, and any configuration settings

Prompt Engineering Standards
Consistency: Use identical core instructions across models, adapting only for platform-specific formatting
Reproducibility: Provide exact prompts in appendix, including system messages and parameters
Variation Rationale: Explain why different prompt approaches were selected for different tasks
Technical Documentation
Required Elements:

Platform access methods and any setup challenges encountered
Model response time and any technical limitations observed
Prompt token counts and response lengths for cost/efficiency analysis
 

5. Enhanced Evaluation Methodology
Quantitative Assessment Framework
Scoring System: 4-point scale for each selected metric

4 - Exceptional: Exceeds professional standards, minimal to no errors
3 - Proficient: Meets professional standards, minor errors that don’t affect utility
2 - Developing: Partially meets standards, noticeable errors requiring revision
1 - Inadequate: Falls below professional standards, major errors or missing elements
Qualitative Analysis Requirements
Pattern Recognition: Identify consistent strengths/weaknesses across models
Context Sensitivity: Analyze how models perform differently across task types
Failure Analysis: Systematic examination of significant errors or inappropriate responses
Statistical Considerations
Sample Size: Minimum 3 distinct inputs per task per model (9 total per task)
Significance Testing: Not required but encouraged for students with statistical background
Confidence Intervals: Acknowledge limitations of small sample sizes in conclusions
