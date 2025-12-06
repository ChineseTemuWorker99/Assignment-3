CISC 101: Final Assignment - Course Concept Mapping
===================================================

Noah Arega

Travel Planner System Analysis
------------------------------

Assignment Overview
-------------------

Throughout CISC 101, you've learned foundational concepts in prompt engineering and software engineering practices. You've applied these concepts in building both a Research Paper Summarizer and a Travel Planner application.

In this final assignment, you will reflect on your learning by analyzing the completed Travel Planner system (from TP7 and TP8) and identifying where each course concept appears in practice.

### 

Required Materials
------------------

You will need access to:

1. **TravelPlanner-SystemPrompt-final.md** (provided in TP7)

2. **TravelPlanner-Reference-final.md** (provided in TP7)
   The original unedited versions are attached for convenience. 

* * *

Assignment Task
---------------

Complete the **Course Concept Mapping Table** below by identifying where and how 5 key course concepts appear in the Travel Planner prompt system.

### For Each Concept, You Must Provide:

1. **Module(s)/ Where Found**: Which module(s) or section(s) contain this concept?
   
   * Example: "Module 3 - Feasibility & Guardrails" or "System Prompt - Boundaries"

2. **Specific Example**: A direct quote or close paraphrase from the system files
   
   * Must be actual text from TravelPlanner-SystemPrompt-final.md or TravelPlanner-Reference-final.md
   * Use quotation marks for direct quotes

3. **Explanation (2-3 sentences)**:
   
   * Explain how this example demonstrates the concept
   * Show why it matters for the system's functionality
   * Connect to what you learned in class about this concept
     
     

Use the table below to input your answers. The first row is an example.

| **Concept**                      | **Where it is Found**               | **Specific Example/Quote from the System**                                          | **Explanation (2-3 sentences)**                                                                                                                                                                                                                                                                                                                                                                 |
| -------------------------------- | ----------------------------------- | ----------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Conditionals (if/then logic)** | Module 3 - Feasibility & Guardrails | "If meal cost > user's budget → switch to a cheaper restaurant of similar cuisine." | This demonstrates conditional logic where the system checks a condition (meal cost exceeds budget) and executes a specific action (finding a cheaper alternative) when the condition is true. The if/then structure ensures the plan remains within the user's financial constraints while maintaining the desired cuisine type. This guardrail enhances the system's robustness and user-friendliness. |
| **Loops**| Module 2 - Plan Builder | "Morning --> near lodging. Midday --> nearby attraction. Afternoon --> different theme. Evening --> restaurant or optional event | This is a programming loop where the system repeats the same scheduling steps for each day of the trip. The loop guarantees consistency and efficiency by applying the same logic to generate daily plans. This is how loops structure repeated operations in prompt-based systems                                                                                                                                                                                                                                                                                                                                    |
| **Hallucination Mitigation**     |Module 3 - Feasibility and Guardrails| "Do not simulate bookings or reviews"| This is a hallucination prevention rule that stops the system from generating nonexistent reservations/review data. Guardrails like this ensure the system does not misinform the user by fabricating information and only gives them safe, factual responses. This is how model creativity is inherently constrained when accuracy is required                                                                                                                                                                                                                                                                                                                                  
| **Specification Design***| Module 1 - Intake & Setup | "Ask only what's essential... Ask all of these in one friendly message"| This defines clear instructions for system behavior. This concept specifies exactly how the assistant must gather user info, setting strict rules for phrasing and structure. This is how well-designed specifications reduce ambiguity and ensure consistent model performance                                                                                                                                                                                                                                                                                                                                                                                            |
| **Data Structures** | Module 1 - Intake & Setup | "Collect and normalize user info... store internally in JSON format"| JSON is an example of a structured data model that prioritizes user preferences and constraints. The stored JSON helps the Travel Planner produce coherent and consistent itineraries. This is how using data structures maintains state and ensures information persists across steps                                                                                                                                                                                                                                                                                                                                                                                      |
| **Few-shot prompting**| Module 4 - Render & Refine| "A relaxed 3-day cultural getaway in Kyoto for two travelers, focusing on temples, food, and scenic walks..."|This is an example of a classic few-shot prompt: the system provides a full sample itinerary that the model implicitly imitates. Displaying the intended output format guides the assistant to follow the same or similar style, structure, and tone. This is how few-shot examples improve reliability by modeling expected behavior|

FAQs
--------------------------

**Q: Can the same module be used for multiple concepts?** 
A: Yes, many modules demonstrate multiple concepts. Just make sure your examples and explanations are tailored for each concept.

**Q: How long should my explanations be?** 
A: 2-3 complete sentences. 


