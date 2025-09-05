# Job-Ready Career Coach MVP

A modern web application that analyzes resumes against job descriptions to provide personalized action plans for becoming job-ready.

## 🎯 Core Value Proposition

**"Know exactly what skills to learn before applying for any job"**

Upload your resume and a job description, get a personalized action plan with specific tasks to become job-ready in weeks, not months.

## 🚀 Features

### ✅ Task 1: Modern Flask Setup + File Upload 
- [x] Flask app with modern, minimal UI using Tailwind CSS
- [x] File upload functionality for PDFs, DOCX, and text files
- [x] Text area inputs for pasting content
- [x] Responsive, mobile-first design
- [x] Basic database setup with SQLAlchemy
- [x] Drag-and-drop file upload with visual feedback

### ✅ Task 2: Text Processing & Skill Extraction 
- [x] Parse uploaded resume to extract skills and experience
- [x] Parse job description to identify required skills
- [x] Create skill taxonomy and matching system
- [x] Store parsed data in database
- [x] Comprehensive skill extraction with 8 categories
- [x] Experience level and education extraction
- [x] Skill importance detection (critical vs preferred)

### ✅ Task 3: Skill Gap Analysis Engine 
- [x] Calculate skill match percentage
- [x] Identify missing critical skills
- [x] Generate visual gap analysis
- [x] Show overall job readiness score
- [x] Comprehensive gap analysis with skill level assessment
- [x] Readiness score calculation with critical/preferred weighting
- [x] Summary generation with recommendations

### ⏳ Task 4: Personalized Action Plan Generator 
- [x] Generate specific tasks for missing skills
- [x] Prioritize tasks by impact
- [x] Provide learning resources and time estimates
- [x] Track task completion and progress

## 🛠 Tech Stack

- **Backend**: Flask + SQLAlchemy
- **Frontend**: Tailwind CSS + Vanilla JavaScript
- **Database**: SQLite (development)
- **File Processing**: PyMuPDF (PDF), python-docx (Word)
- **Testing**: pytest + pytest-flask

## 📦 Installation

### Local Development

1. **Clone the repository**
   ```bash
   cd job_coach_mvp
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   python app.py
   ```

4. **Open your browser**
   ```
   http://localhost:5000
   ```


## 🧪 Testing

Run the test suite:
```bash
pytest tests/
```

Run specific test files:
```bash
pytest tests/test_text_processor.py
pytest tests/test_app.py
```

## 🔄 User Journey (2-3 minutes)

1. **Upload Resume** (15 sec): Drag resume PDF or paste text
2. **Add Job Description** (15 sec): Paste job posting from LinkedIn
3. **See Skill Analysis** (30 sec): View readiness score and gaps
4. **Get Action Plan** (30 sec): Receive specific tasks with timeline
5. **Track Progress** (30 sec): Mark tasks complete, see improvement


## 📊 Success Metrics

### Core Functionality
- [ ] Upload and analyze in under 2 minutes
- [ ] Accurate readiness score calculation
- [ ] Relevant, specific action plans
- [ ] Progress tracking motivates completion

### User Experience
- [ ] Modern, professional interface
- [ ] Mobile-responsive design
- [ ] Fast performance (<3 second analysis)
- [ ] Intuitive user flow

## 🚧 Development Status

- **Task 1**: ✅ COMPLETED - Foundation and file upload
- **Task 2**: ✅ COMPLETED - Text processing and skill extraction
- **Task 3**: ✅ COMPLETED - Skill gap analysis engine
- **Task 4**: ✅ COMPLETED - Action plan generator

## 🤝 Contributing

This is an MVP project. The current focus is on completing the core functionality:

1. **Text Processing**: Extract skills from resumes and job descriptions
2. **Gap Analysis**: Compare skills and calculate readiness score
3. **Action Plans**: Generate specific, actionable tasks

## 📝 License

This project is for demonstration and validation purposes.

---

**Value Proposition**: "Stop guessing what skills you need. Get a personalized roadmap to become job-ready in weeks, not months."
