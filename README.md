## Job Appliocation Crew- Multi-Agent System

### Overview
This project implements a multi agent system for automating the process of analyzing job postings, tailoring resume, writing cover letters, and preparing for interviews. 

### Project Structure

- **Notebook:** `job_application_crew.ipynb`.
- **Resume File:** `MyFakeResume.md`(used for semantic search and analysis).
- **Environment Config:** `.env`(stores API keys and model configuration).

### Tools Used
- `SerperDevTool` - (Web searching).
- `ScrapeWebsiteTool` - (Web scraping).
- `FileReadTool` - (Document reading).
- `MDXSearchTool` - (Semantic search).

### Agent Architecture
**1. Tech Job Researcher (researcher Agint)** Extract and job requirements from job posting.

**2. Personal Profiler Analyst (profiler Agent)** Analyze resumes, personal projects, and other data sources to highligh strengths and match them to job requirements.

**3. Resume Strategist (resume_strategist Agent)** Strategic resume optimization and tailoring.

**4. Cover Letter Writer (cover_letter_writer Agent)** Create compelling and customized cover letters.

**5. Interview Coach (interview_preparer Agent)** Create interview questions and talking points based on the resume and job description.

### Installation and Setup

1. Download the repository.
2. Install the required Python packages.
3. Create a `.env` file in the root directory to store your API keys:
```python
   OPENAI_API_KEY=your_openai_api_key
   SERPER_API_KEY=your_serper_api_key
   OPENAI_MODEL_NAME=gpt-4.1-mini
```
4. Open the Jupyter Notebook and configure your analysis parameters.
5. Run the cells.

### Output Files

The project generates three files:
- `tailored_resume.md`
- `cover_letter.md`
- `interview_materials.md`

###Contribution:
Feel free to fork, extend, or add new agents to expand the pipeline.

