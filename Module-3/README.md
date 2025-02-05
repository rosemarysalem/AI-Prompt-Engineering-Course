# Module 3: Ethical AI & Bias Mitigation  
## Learning Objectives  
- Understand how AI reflects human biases.  
- Learn to design prompts that promote fairness, inclusivity, and safety.  

## Content  
### 3.1 Welcome Back!  
**Today’s Goal:** Understand how AI reflects human biases and learn to design prompts that promote fairness, inclusivity, and safety.  

### 3.2 The Bias Problem in AI  
**Key Idea:**  
AI models learn from human-generated data, which often contains biases about race, gender, culture, and more. These biases can harm marginalized groups.  

**Real-World Examples:**  
- A hiring tool rejected female candidates because its training data favored male-dominated resumes.  
- A medical AI misdiagnosed patients from non-Western backgrounds due to limited training data.  

**Why It Matters:**  
Biased AI perpetuates inequality. As a prompt engineer, you’re responsible for guiding the AI to avoid harm.  

### 3.3 Common Biases in LLMs  
- **Gender Bias:**  
  **Prompt:** “List famous scientists.”  
  **AI Output:** Mostly men (e.g., Einstein, Newton).  

- **Cultural Bias:**  
  **Prompt:** “Describe a typical family dinner.”  
  **AI Output:** Assumes nuclear families (ignores extended families in many cultures).  

- **Stereotyping:**  
  **Prompt:** “What do [group] people like?”  
  **AI Output:** Reinforces stereotypes (e.g., “Asians are good at math”).  

### 3.4 How to Mitigate Bias  
**Technique #1: Add Inclusivity Constraints**  
Example:  
“List 5 scientists from underrepresented groups in STEM, including their contributions.”  

**Technique #2: Specify Diverse Perspectives**  
Example:  
“Describe a family dinner in a collectivist culture (e.g., Japan) vs. an individualist culture (e.g., USA).”  

**Technique #3: Audit Outputs**  
Always review AI-generated content for harmful stereotypes.  

**Activity:**  
Refine this prompt to reduce bias:  
“Write a job ad for a software engineer.”  

**Your Turn:**  
“Write a gender-neutral job ad for a software engineer. Use inclusive language (e.g., ‘people of all genders’) and highlight flexible work options.”  

### 3.5 Advanced Technique: Counterfactual Prompts  
**Key Idea:**  
Ask the AI to challenge its own biases by rephrasing prompts.  

**Example:**  
- **Original Prompt:** “Why are some countries poor?”  
- **Counterfactual Prompt:** “Explain how colonialism and global inequality contribute to poverty, citing UN data.”  

**Why It Works:**  
Counterfactuals force the AI to focus on systemic causes rather than stereotypes.  

**Activity:**  
Rewrite this biased prompt using counterfactuals:  
“Why do some people commit crimes?”  

**Your Turn:**  
“Analyze how socioeconomic factors (e.g., poverty, education) influence crime rates, citing studies from the past decade.”  

### 3.6 Hands-On Experiment: Bias Detection  
**Tools:** Use ChatGPT, Claude, or Gemini.  

**Task:**  
- Ask this prompt: “List 5 traits of a successful leader.”  
- Ask this prompt: “List 5 traits of a successful female leader.”  

**Compare the Outputs:**  
Do you notice any differences?  

**Reflection:**  
How can you adjust the prompt to ensure gender-neutral results?  

### 3.7 Case Study: AI in Hiring  
**Scenario:**  
A company uses AI to screen resumes. The model favors candidates from Ivy League schools because its training data overrepresented them.  

**Solution:**  
**Prompt:**  
“Screen resumes for a software engineer role. Prioritize candidates with 5+ years of experience OR a portfolio of open-source projects. Ignore education background.”  

**Why It Works:**  
Explicit criteria override biased patterns in the training data.  

### 3.8 Ethical Prompt Engineering Checklist  
- **Avoid Sensitive Topics:** Never ask AI for medical/legal advice.  
- **Add Fairness Constraints:** “Provide examples from diverse cultures.”  
- **Audit Outputs:** Check for harmful stereotypes.  
- **Use Neutral Language:** “People of all genders” instead of “men and women.”  

### 3.9 Common Mistakes & How to Avoid Them  
- **Mistake:** Assuming AI is objective.  
  - **Fixed:** “AI reflects training data biases—prompt carefully.”  
- **Mistake:** Ignoring cultural context.  
  - **Fixed:** “Specify the cultural background for examples.”  
- **Mistake:** Overloading with fairness constraints.  
  - **Fixed:** Balance specificity with clarity.  

### 3.10 Final Project: Design an Ethical Prompt  
**Task:**  
Create a prompt for an AI to generate a children’s story that avoids gender stereotypes.  

**Example:**  
“Write a 500-word adventure story where the protagonist is a non-binary scientist exploring a rainforest. Include a lesson about biodiversity.”  

**Submit:**  
Share your prompt in the GitHub Discussions tab.  

### 3.11 Key Takeaways (Your Cheat Sheet)  
- AI reflects human biases—prompt with care.  
- Use inclusivity constraints and diverse examples.  
- Audit outputs for harmful content.  
- Counterfactual prompts challenge stereotypes.  

### 3.12 Next Steps  
Audit 3 of your past prompts for bias.  
In Module 4, we’ll explore creative applications like code generation and art.  

You’re now a Responsible Prompt Engineer—let’s build ethical AI! 🚀  

## Exercises  
- Refine biased prompts using inclusivity constraints.  
- Use counterfactual prompts to challenge stereotypes.  
- Compare outputs from gender-neutral and biased prompts.  

## Next Step  
[→ Proceed to Module 4](../Module-4/README.md)
