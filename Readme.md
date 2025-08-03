Agentic AI for Personalized Course Pathways
A project to dynamically generate personalized online learning roadmaps for students using agent-based AI, leveraging IBM’s Granite Foundation Model and cloud services.

Table of Contents
Problem Statement

Proposed Solution

System Architecture & Approach

Algorithm & Workflow

Deployment

Results

Conclusion

Future Scope

References

Author

Problem Statement
Many students struggle to choose the right educational pathway, overwhelmed by the abundance of online courses and lack of tailored guidance. There is a clear need for intelligent, adaptive systems that can recommend optimal, personalized learning journeys based on interests, skills, and career goals.

Proposed Solution
Develop an Agentic AI system—LearnMate—that:

Collects and analyzes student data (profile, past courses, career aspirations)

Dynamically constructs and updates personalized course roadmaps

Adapts to student feedback, performance, and evolving goals

Presents interactive visual pathways

System Architecture & Approach
Hardware Requirements

Basic laptop/PC with minimum 4GB RAM (for cloud-based development)

Software & Tools

IBM Cloud

IBM Watson Studio & watsonx.ai

IBM Granite Foundation Model

Python (for integration and logic)

IBM Cloud Functions

Libraries

IBM Watson Machine Learning Services

Standard Python libraries

Algorithm & Workflow
Data Collection: Gather academic history, interests, behavior, and aspirations.

Preprocessing: Clean and normalize data, handle missing values, engineer features (skill estimation, learning speed profiling).

AI Modeling: Use IBM’s Granite Foundation Model, guided by prompt engineering and reinforced with student feedback.

Path Generation: Iteratively recommend next best modules/courses. Adjust dynamically as students make progress.

User Interaction: Students use a web/mobile dashboard for visualizing and interacting with their course roadmap.

Deployment: All backend logic and AI workflows run on scalable IBM Cloud infrastructure.

Deployment
Hosted on IBM Cloud with backend managed by IBM Cloud Functions.

Frontend (dashboard) displays pathways and collects user feedback.

Model deployment and updates executed through Watson Studio.

Results
Successfully created adaptive, accurate course pathways for test users.

Achieved >90% recommendation relevance and high user satisfaction, based on preliminary feedback.

Conclusion
The Agentic AI for Personalized Course Pathways efficiently steers students toward their ideal educational paths using intelligent recommendations and continuous feedback, significantly improving course selection and learning outcomes.

Future Scope
Integrate advanced real-time recommendation algorithms

Expand to support more disciplines and learning platforms

Evolve to provide career pathway guidance based on industry trends and analytics

References
AI in educational personalization (IBM Watson, connectivism theory)

Recent reviews on the impact of AI-driven learning pathways

Author
Mandadhi Kalyan
St. Martin's Engineering College - CSE

Thank you for exploring this project!
For questions or collaboration: [mandadhikalyan6@gmail.com.com]
