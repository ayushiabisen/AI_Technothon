# Team42: AI-Technothon

## [Problem statement](https://community.persistent.com/question/1713/problem-statement-6-training-recommender-and-assessment-evaluator/)
Develop a web application for automated assessment and personalized training recommendations. The application should allow users to take an assessment, use MCQ Genie as base reference, and based on their outcome score, generate another set of MCQs of varying levels to further evaluate their knowledge. Additionally, the application should recommend training courses that align with the user's performance and are of various levels to cater to their specific needs. The objective is to provide users with targeted training opportunities based on their assessment results, facilitating their continuous learning and skill development. Focusing on user-friendly interfaces, accurate assessment algorithms, and relevant training recommendations.

### Objective:  
To do skill gap analysis and personalized training suggestions for the engineers using generative AI with respect to project and account

### Modules:
- MCQ generation and assessment module & Community Quiz features
- Skill gap analytics
- Personalized training recommendations
- UI

---
### Approach used:
- Started with provided datasets(result of MCQ Genie)
- Selected questions for first assessment from the dataset
- Selected remaining questions for second assessment
- As user will be answering questions, score is recorded per sub-topic
- Analytics: Results of score per sub-topic is shown and also recommended courses/videos
---
### Tech Stack: 
We made a front-end application with these technologies:
- React JS
- Redux
  Others:
- ChartJS
- YouTube API
---
### Installation:
```
cd team42 
npm install
npm run dev
```

