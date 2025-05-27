# UNIT 3 – Heuristic Evaluation of an Existing Website or App
## AIM
To perform heuristic evaluation on two competing apps/websites, propose design improvements, and evaluate the impact of the improvements using A/B testing.

## PROBLEM STATEMENT
Many apps/websites suffer from poor user experience (UX) due to design flaws. This experiment aims to compare two competing platforms, identify usability issues through heuristic evaluation, suggest improvements, and assess the impact of changes using A/B testing.

## DESIGN STEPS 
### Select Competing Apps/Websites:

App A: Zomato
App B: Swiggy

### Conduct Heuristic Evaluation

Evaluate both apps using Nielsen’s 10 Usability Heuristics:
Visibility of system status
Match between system and real world
User control and freedom
Consistency and standards
Error prevention
Recognition rather than recall
Flexibility and efficiency of use
Aesthetic and minimalist design
Help users recognize, diagnose, and recover from errors
Help and documentation

### Identify Usability Issues:

Zomato: Overcrowded interface, poor error messaging
Swiggy: Inconsistent button labels, missing confirmation on cancellation

### Propose Design Changes:

Zomato: Simplify layout, add tooltips for error messages
Swiggy: Unify button labels, add cancellation confirmation dialog

### Design A/B Testing:

A Version: Original design
B Version: Modified design

Users split into two groups (randomly assigned)
Metrics: Task completion time, error rate, satisfaction score (via post-task survey)

### Conduct User Testing:

10 users for each version
Tasks: Search food item, place order, cancel order

## DESIGNS
### Zomato - Original (A):

Home screen with multiple banners, mixed fonts
No tooltip or explanation when order fails
![image](https://github.com/user-attachments/assets/807bb394-cc8c-4a78-bd97-d59f62923cf4)


### Zomato - Modified (B):

Minimal layout with clear sections
Error tooltip on order failure explaining issue
![image](https://github.com/user-attachments/assets/fe77a430-afdf-4f81-ba4d-eabd1bd32cbf)


### Swiggy - Original (A):

"Go Back", "Return", and "Cancel" buttons used interchangeably
Order cancellation happens instantly
![image](https://github.com/user-attachments/assets/caf6c224-2c46-4cdb-a185-86d517d05a02)



### Swiggy - Modified (B):

All buttons renamed to "Cancel Order" or "Go Back" appropriately
Confirmation dialog before cancellation
![image](https://github.com/user-attachments/assets/66c65d64-8548-4e24-bca1-b405e273c68e)



## RESULTS
App	Version	Task Completion Time (avg)**	Errors	User Satisfaction (1–5)
Zomato	A	2.4 min	5	3.2
Zomato	B	1.8 min	1	4.4
Swiggy	A	2.1 min	4	3.5
Swiggy	B	1.7 min	0	4.6

## Conclusion
The heuristic evaluation helped identify several UX issues in Zomato and Swiggy. After implementing suggested design improvements, A/B testing showed clear gains in task efficiency, reduced errors, and increased user satisfaction. This validates the effectiveness of UX redesign guided by heuristic principles.

