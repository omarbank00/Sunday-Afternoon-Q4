Large Language Models are: sophisticated autocomplete systems

# Understanding TopK

- Top-k (static)
- top_k = 10 (always prefer top 10 words)
- top_k = 2 (always prefer top 2 words)

## Example (TopK = 2)
- Aj weather bhot 
-> acha
-> bura
-> Thanda 
-> garam 

- Main kal market (Topk = 1)
-> gaya
-> jounga
-> nahi jounga




agent= Agent(
	name="",
        instruction="",
	model_settings = ModelSettings()

# Understanding TopP

- Top_P (Dynamic) 0.8%

## Example
- Aj weather bhot
-> acha (50%)
-> phele say behtr (30%)
-> normal
-> Thanda
-> garam
1. Top_p is dynamic
2. In Top_p we set the threshold
3. When selecting a next word combine probability from the threshold will be nominated



# How Temperature, TopK and TopP work together

- Conservative: Temperature 0.1, Top-P 0.9, Top-K 20
Temperature (Supreme Controller): Low
Top-P 90% (Second Preference) = High
Top-K 20 (least Preference) = Low
 



# Understanding Zero, One and Few Shots Prompt

====================================
Shot means Examples

1. Zero Shot Prompting: Prompt that does not contains any exmaples
2. One Shot: Prompt that contains only one example
3. Few Shot: Prompt that contains 3-5 examples



# Understanding Role and System Prompting

- Role + System Prompting can be used together.
- You are a Software engineer your expertise lies in writing APIS in Python FASTPI. Your task is to give highly optimize solution for the endpoints I request. The APIS should cover timeouts and rate limiting.





# Helping Prompts to Learn and Practice for the exams and homework
- *Prompt* You are a prompt engineering expert. Your task is to make the fundamentals and complex prompt engineering concept easy to understand. I would be pasting the text from a Highly maintained Github Repo. Keep your vocabulary simple and easy to understand. 

After your explanation I would provide a summary of what I have understand. Rate my summary out of 10 so I would get a better idea that where I am standing.


