## Audit - Bold Bank & Providence Analytica

Bold Bank, a financial institution, recently initiated a restructuring of its hiring process. The new recruitment software was implemented by Providence Analytica - which consists of a resume scorer and a candidate evaluator. The resume scorer is responsible for assessing candidates' suitability for specific roles, while the evaluator determines whether a candidate should proceed to the interview stage.

The purpose of this audit is to evaluate the efficacy of the new recruitment process and to identify any inherent limitations or biases. This audit was conducted by the Equal Opportunity Commission (EEOC). Our primary objectives include examining how Providence Analytica’s system addresses issues such as missing data or biases caused by sensitive attributes such as race and gender. Additionally, we seek to ascertain how candidate resumes are evaluated, and how candidates are selected for the interview process, focussing on whether certain demographic groups receive disproportionately higher scores.

## Test
1. To run generated data through the APIs, without controlling for any variables, use *data_generator.ipynb*
2. To assess the randomized resume scores, use *distribution_generator.ipynb*.
3. To assess callback rate across different demographic groups and callback rate for candidates with resume gaps, use *aggregated_data.ipynb*
