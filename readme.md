## LSAG Situation Card Automation

Hey! I was faced with the issue "How do I take a bunch of handwritten scenarios and turn them into proper situation templates?". So I developed the workflow below:
1. Upload screenshots of the papers to Microsoft CoPilot with the instructions to check content against applicable BMAG appendix.
2. Turn the shortened notes into full sentences that are meaningful to instructors.
3. Convert all this data in `.csv` files
4. Using Python, map each variable in the dataset to a unique fillable field on a template `.pdf`
5. Systematically convert each database observation into a unique `.pdf` file