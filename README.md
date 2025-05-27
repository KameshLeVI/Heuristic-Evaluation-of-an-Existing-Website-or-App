# UNIT 3 – Heuristic Evaluation of an Existing Website or App
## AIM
To perform heuristic evaluation on two competing apps/websites, propose design improvements, and evaluate the impact of the improvements using A/B testing.

## PROBLEM STATEMENT
Many apps/websites suffer from poor user experience (UX) due to design flaws. This experiment aims to compare two competing platforms, identify usability issues through heuristic evaluation, suggest improvements, and assess the impact of changes using A/B testing.

## DESIGN STEPS
Select Competing Apps/Websites:

App A: Zomato

App B: Swiggy

Conduct Heuristic Evaluation
Evaluate both apps using Nielsen’s 10 Usability Heuristics:
![20250527_0927_App UX Heuristic Analysis_simple_compose_01jw7y42bee18axmm711mfa2zx](https://github.com/user-attachments/assets/1dd9e413-9418-4506-9083-5db37b4caa5c)

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

Identify Usability Issues:

Zomato: Overcrowded interface, poor error messaging

Swiggy: Inconsistent button labels, missing confirmation on cancellation

Propose Design Changes:

Zomato: Simplify layout, add tooltips for error messages

Swiggy: Unify button labels, add cancellation confirmation dialog

Design A/B Testing:

A Version: Original design

B Version: Modified design

Users split into two groups (randomly assigned)

Metrics: Task completion time, error rate, satisfaction score (via post-task survey)

Conduct User Testing:

10 users for each version

Tasks: Search food item, place order, cancel order

## DESIGNS
Zomato - Original (A):

Home screen with multiple banners, mixed fonts

No tooltip or explanation when order fails
![1](https://github.com/user-attachments/assets/e77fcb9a-301a-4841-8fa6-d52409c7eaab)

Zomato - Modified (B):

Minimal layout with clear sections

Error tooltip on order failure explaining issue
![2](https://github.com/user-attachments/assets/29ac1f6b-f1f8-4f57-99a1-2f6889100355)

Swiggy - Original (A):

"Go Back", "Return", and "Cancel" buttons used interchangeably

Order cancellation happens instantly
![3](https://github.com/user-attachments/assets/fabe47b3-c584-4f47-8970-88b60108b823)


Swiggy - Modified (B):

All buttons renamed to "Cancel Order" or "Go Back" appropriately

Confirmation dialog before cancellation
![4](https://github.com/user-attachments/assets/1f61ff78-6c0d-4d1c-8c08-e1df27ce0c9f)


## RESULTS
App	Version	Task Completion Time (avg)**	Errors	User Satisfaction (1–5)
Zomato	A	2.4 min	5	3.2
Zomato	B	1.8 min	1	4.4
Swiggy	A	2.1 min	4	3.5
Swiggy	B	1.7 min	0	4.6

Conclusion
The heuristic evaluation helped identify several UX issues in Zomato and Swiggy. After implementing suggested design improvements, A/B testing showed clear gains in task efficiency, reduced errors, and increased user satisfaction. This validates the effectiveness of UX redesign guided by heuristic principles.

