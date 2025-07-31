## Formula 1 Sprint Race Analysis (2024 Season)

This file contains natural language questions tested with a large language model (LLM), model responses, and validation using Python.

---

### Prompt: Which driver earned the most sprint points overall?
Answer: Max Verstappen with 38 points  
Model Accuracy: Correct  
Validation Method: Summed all sprint points grouped by driver and sorted to find the top scorer.

---

### Prompt: Which team earned the most sprint points?
Answer: Red Bull Racing Honda RBPT  
Model Accuracy: Correct  
Validation Method: Aggregated points per team and identified the team with the highest total.

---

### Prompt: Which driver had the best average finishing position?
Answer: Max Verstappen (lowest average position)  
Model Accuracy: Correct  
Validation Method: Calculated the mean finishing position for each driver and identified the lowest average.

---

### Prompt: Which team was the most consistent in sprint races?
Answer: Team with the lowest variation in finishing positions (e.g., Red Bull)  
Model Accuracy: Mostly correct  
Validation Method: Calculated standard deviation of finishing positions per team to assess consistency.

---

### Prompt: Did starting grid position strongly impact final results?
Answer: Yes, positive correlation found  
Model Accuracy: Correct if LLM mentions correlation strength  
Validation Method: Measured correlation between starting grid position and final finishing position.
---

### Prompt: Is there a correlation between improvement and sprint points?
Answer: Yes, mild positive correlation  
Model Accuracy: Acceptable if trend is mentioned  
Validation Method: Created a new metric for improvement (Starting Grid - Final Position), then correlated it with sprint points.

---

### Prompt: Is there a correlation between starting grid and sprint points?
Answer: Slight to moderate correlation expected  
Model Accuracy: Partially correct  
Validation Method: Measured correlation between starting grid position and sprint points earned.

---

### Prompt: Does improvement in position lead to more points?
Answer: Generally yes  
Model Accuracy: Acceptable if model links improvement with scoring  
Validation Method: Analyzed the correlation and visual relationship between position improvement and points scored.
"""
