# Analyzing GRE Diagnostics Tests

## Aim
In this repo, I explore how well I did on the GRE diagnostics tests provided by Kaplan and by ETS.

## What's the data?
The Kaplan tests provided the following information for every question:
- Difficulty level (low, medium, high)
- Topic (Sets and Statistics, Arithmetic, Proportions, Geometry, Number Properties, Algebra, Data Interpretation)
- Seconds (how long it took to answer the question)
- Answer (1/0)

The ETS test provided only Answer (1/0). To the best of my ability, I tried to objectively classify the difficulty level and topic of every question. 

In the notebook, I mainly rely on data from Kaplan. The final section of the notebook is a replication of the first sections (where possible) but with the ETS data appended to the Kaplan data.

In order to get the Kaplan data, I did the following per test:
- Take a screenshot of each question
- Combine the screenshots in a PDF
- OCR the PDF
- Extract relevant info from OCR:ed PDF
- Import to Pandas and take it from there

## End result?
This exercise helped me understand where my weaknesses lie, which topics I must get better at and how consistent I am. For example, understanding how ETS write the Proportions questions and how to answer them counts as low hanging fruit. It is much easier to improve one's results in Proportions or Data Interpretation by figuring out how they would like you to answer than to learn new concepts in Number Properties.
