# Exno.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE: 09/05/2025                                                                       
### REGISTER NUMBER : 212222040039
### Aim:
To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts.

## Tools Required:
1.AI text generation platforms (ChatGPT, Claude, etc.)

2.Word/Excel for prompt and response documentation

3.Internet access for AI model testing (if needed)

## Theory:
Prompt engineering tailors inputs to guide AI models for accurate and user-centric responses. 
The three prompting methods used are:

1.Straightforward Prompting:
                     Direct command or question to extract a concise response.

2.Tabular Format Prompting:
                     Organizing complex or multi-point information into tables for clarity.

3.Preceding Question Prompting:
                     Creating a back-and-forth conversational flow to solve layered user issues.

## Experiment Procedure:
We simulated 3 core healthcare service scenarios:

1.Symptom Checker
2.Appointment Scheduling
3.Health FAQs

Each scenario was tested using all three prompting techniques.

## Scenarios and Prompts
# Scenario 1: Symptom Checker
#  Prompt	                                                            Prompting Type	                 Bot Response
1."I have a sore throat and fever."                                	  Straightforward Prompt	         "These symptoms could indicate a viral infection such as flu. Please consider seeing a doctor if it persists."

2."Show possible causes of sore throat and fever with                 Tabular Format Prompt	           Table with columns: Symptom, Possible Cause, Remedy, Urgency Level
suggested remedies in a table."	

3."I feel feverish." ➔ "Do you have other symptoms?" ➔ "Yes          Preceding Question Prompt        Progressive, engaging diagnosis flow
sore throat and chills." ➔ "You might have a cold or flu. 
Do you want to find a clinic nearby?"	

## Scenario 2: Appointment Scheduling
# Prompt	                                                             Prompting Type                    	Bot Response
1."Book an appointment with a dentist tomorrow morning."	             Straightforward Prompt	            "Your appointment with a dentist is scheduled for 10 AM tomorrow."

2."List available time slots for Dr. Mehta on Friday in a table."	     Tabular Format Prompt	             Table showing Time Slots, Availability, Location

3."I need a cardiologist." ➔ "Preferred time?" ➔                      Preceding Question Prompt	          Dynamic scheduling interaction
"Evening today." ➔ 
"Dr. Rao is available at 6:30 PM. Shall I book it?"	

## Scenario 3: Health FAQs
# Prompt	                                                                Prompting Type	                        Bot Response
1."What is the normal blood pressure range?"	                            Straightforward Prompt	               "Normal blood pressure is usually around 120/80 mmHg."

2."List common health parameters and their normal ranges in a table."	    Tabular Format Prompt	                  Table with columns: Parameter, Normal Range, Measurement Frequency

3."Is 140/90 high?" ➔ "Yes, it may indicate stage 1 hypertension." ➔     Preceding Question Prompt	             Helpful follow-up guidance
"What should I do?"	

## Analysis


# Prompting Type:         Best Used For               Strengths                                Weaknesses
Straightforward     	    Quick                       factual health tips	Speedy               informative	May miss nuance
Tabular Format            Health stats                comparisons	Very clear                   easy to scan	Not interactive
Preceding Question        Symptom triage              appointment booking	Natural              patient-like interaction	Slower


## Evaluation and Observations
1.Straightforward Prompting gave rapid answers suitable for FAQ-style questions.

2.Tabular Prompting worked best for structured medical data like normal ranges or time slots.

3.Preceding Question Prompting gave a personalized, context-aware experience for health concerns.

## Conclusion:
The AI-powered healthcare chatbot successfully used three prompting methods to handle health inquiries, symptoms, and appointment needs. Prompting variation improves flexibility and user satisfaction.

## Result:
Prompts were successfully implemented in a healthcare assistant context, demonstrating the chatbot’s capability to assist users with health-related needs using effective prompt engineering.
