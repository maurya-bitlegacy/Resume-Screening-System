# Resume-Screening-System
Screens resumes based on skills of applicants.

Train set: More than 1000 resumes of over 10 job categories extracted from livecareer.com. Used to learn skills needed for each job category.
Uses a custom spacy pipeline for recognition of skills from raw text. Skill pattern from Microsoft is used(https://github.com/microsoft/SkillsExtractorCognitiveSearch/blob/master/data/skill_patterns.jsonl)

2 usecases: Get the required skills for a job category by finding the top skills of applicants of this job category in the train set, OR get the skills required from the JD itself.
Find the skills of the candidates, get a match score and return the candidate resumes with the highest match score.

The spacy model can be generated in Analysis.ipynb
