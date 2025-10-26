# Q) What is Chain of Thoughts
Used for complex quries
1. Step by step reasoning for complex problems
2. Think before answering
3. Show working

### Example: 
1. Maths Problem (Algebra problem)
2. Making a Dish
3. Trip to Northern Area 
4. Buying a car
5. Telling doctor about your symptoms,
6. Relationship chain: apke mama kay bete ki mami ki ammi ki behn ka beta ka dost ka bhai apka kya hua?, When I was 4 my friend was half my age now I am 20 what is the age of my friend

### Prompts: 
1. Buying a car
2. Telling doctor about your symptoms,
3. Relationship chain: apke mama kay bete ki mami ki ammi ki behn ka beta ka dost ka bhai apka kya hua?, When I was 4 my friend was half my age now I am 20 what is the age of my friend

### Prompt: 
"I want to invest in crypto but keeping the market trends and fluctuations in mind. Think step by step: First, check current trends. Second, look at risks. Third, suggest safe options."

### Prompt 2: 
"For any investment query, think step by step: 1. Analyze trends. 2. Check risks. 3. Suggest options." This helps the agent avoid rushed, bad decisions."


# Q) What is ToT?
1) Explore MULTIPLE paths or possible ways.
2) Thinks in different paths
3) We could say Tell us 3 possible ways
4) Thinks Pros and Cons

Eg: 
1. How to control Air Pollution?
2. Tax Collection
Problem: Country developing
Solution: Tax Collection (50%)

Solution One: 
1. High Class (50%)
2. Middle Class: 8%
3. Lower Class 1%

Prompt: I want to improve tax collection using a Tree of Thoughts approach, while considering taxpayer compliance and economic factors. Think 3 approaches for: First, analyze current revenue data. Second, identify common evasion methods. Third, propose three possible ways to implement a tax: a progressive income tax, a value-added tax on goods, and a property tax based on location and value.

 
# Q) What is Self-Consistency?
1. Need confirmation of a particular thing
Example: 
1. Buying a house
2. Confirming 3 different doctors to confirm that disease is actually a Migraine.
3. Asking a friend again and again to confirm about a dinner.
4. Consulting different mechanics about car engine.

Prompt: You are a tax auditor reviewing a business's financial records. To ensure self-consistency in your final report, you must cross-verify the reported annual revenue from three independent sources before confirming the figure.

Check the following three sources for consistency:
- The official Income Statement submitted by the company.
- The total deposits recorded in the company's primary bank statements for the year.
- The sum of all sales invoices issued and logged in their internal accounting software.

# Q) What is ReAct?
Re (Reasoning/Thoughts)
  i. Analyze the Query/Prompt
Act (Action)
  i. Call a tool/API

Prompt: Analyze this taxpayer's query about deduction eligibility.
First, reason through the specific tax rules involved.
Then, call the API to fetch their latest transaction history.
Finally, provide a clear answer based on the combined data.




# Q)How to write an Effective Prompts
1. Be specific and clear
2. Use Action Verbs
3. Tell AI/Agent what to do. Avoid telling AI what NOT to do.
4. Provide examples: Providing the specific design reference to Lovable/vo.dev (Platform to convert design to code)
5. Use variables.

- Prompt: Write an API in Python. Implement all the best practices like Rate-Limiting and spamming. The API should be optimize. The API should be have the POST method. The parameters should be from Pydantic class

- Prompt with Variables: Write an API in {prog_language}. Implement all the best practices like Rate-Limiting and spamming. The API should be optimize. The API should be have the {api_method} method. The parameters should be from {validation} class




# Project Related Discussion

FrontEnd: NextJS
Backend: Python (Programming language)
Backend Framework: FASTAPI

1. Make a FASTAPI endpoint
2. In the FASTAPI endpoint initialize the Agent and initialize the Runner
3. Return the Response to the Frontend


## Javascript
- export async function POST(){}
- export async function GET(){}


## Projects
1. AI Powered Blog website
2. AI powered Resume chatbot
3. AI powered ECommerce
4. Share on LinkedIn








 


