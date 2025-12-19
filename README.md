# Lab Guidelines
## Research, Development, and Academic Collaboration

---

## 1. Purpose of This Repository
This document defines the official guidelines, standards, policies, and workflows
for all research, development, and student projects under this research unit.

All members, including researchers, students, and collaborators, must read and
follow these guidelines before contributing to any repository.

This guideline is designed to ensure:
- Professional research practices
- Reproducibility and sustainability
- Long-term knowledge preservation
- Smooth collaboration across generations of researchers

---

## 2. Research Unit Overview
**Research Unit Name:** Internet of Things and Embedded Systems (IoTES), Nakhon Phanom University, Thailand.
**Organization (GitHub):** IoTES-LAB  
**Head / Principal Investigator:** Dr. Apirak Tooltham  

**Research Scope includes (but not limited to):**
- Internet of Things (IoT) & Embedded Systems
- PM2.5 and Environmental Monitoring
- Artificial Intelligence & Machine Learning
- Data Science & Signal Processing
- Smart Farm, Smart City, and Smart Technologies

---

## 3. GitHub Organization Policy

### 3.1 Account Usage
- Every member must use their **personal GitHub account**
- Account sharing is strictly prohibited
- Institutional or shared accounts are not allowed
- Two-Factor Authentication (2FA) is mandatory for all members

---

### 3.2 Roles and Permissions
| Role | Description |
|-----|------------|
| Owner | Head of research unit / PI |
| Maintain | Senior researchers, PhD/Master students, Research Assistants |
| Write | Undergraduate students, contributors |
| Read | Alumni, external reviewers |

Role assignment is determined by the PI and may be updated as responsibilities change.

---

## 4. Repository Policy

### 4.1 One Project = One Repository
Each research project must have its own repository.

Repository naming convention:

topic-keyword-description

Examples:
- `pm25-lowcost-sensor`
- `edge-ai-dust-detection`
- `smart-farm-iot-platform`

---

### 4.2 Standard Repository Structure
Each repository should follow this structure:

```text
/docs        Project documentation
/data        Dataset or dataset references
/src         Source code
/experiments Experimental scripts
/results     Results, figures, logs
README.md    Project overview


⸻

4.3 README.md Requirements

Every repository must include a README.md containing:
	•	Project objective
	•	Methodology overview
	•	Dataset description
	•	How to reproduce results
	•	Publication status (if any)

⸻

5. Branching Strategy

The standard branching model is:
	•	main
Stable, reviewed, and publishable code only
	•	dev
Integration branch for ongoing development
	•	feature/*
Individual feature or experiment branches

⚠ Direct commits to main branch are not allowed.

⸻

6. Commit Message Convention

Commit messages must follow this format:

[type]: short description

Allowed types:
	•	feat – new feature
	•	fix – bug fix
	•	docs – documentation update
	•	data – dataset update
	•	exp – experiment or evaluation
	•	refactor – code restructuring

Example:

feat: implement PM2.5 sensor calibration algorithm


⸻

7. Pull Request (PR) Policy

All changes must be submitted via Pull Request.

Each Pull Request must include:
	•	Clear description of changes
	•	Related issue number (if applicable)
	•	Experimental results or evidence (for research work)

At least one reviewer approval is required before merging.

⸻

8. Issue Tracking Policy

GitHub Issues must be used for:
	•	Task assignment
	•	Bug reporting
	•	Research discussion
	•	Experiment planning
	•	Feature requests

External chat applications must not be used as the primary task tracking system.

⸻

9. Dataset and Research Ethics Policy
	•	Personal, sensitive, or identifiable data is strictly prohibited without approval
	•	All public datasets must include proper citation
	•	Private datasets must not be shared outside the organization
	•	Data handling must comply with ethical and institutional regulations

⸻

10. Security Policy
	•	Do not commit credentials, API keys, or secrets
	•	Use environment variables (.env) for sensitive configuration
	•	Security incidents must be reported to the PI immediately
	•	Repository access may be revoked if security policies are violated

⸻

11. Publication and Authorship Policy
	•	Authorship is based on actual contribution
	•	Code and dataset contributors must be acknowledged
	•	Repositories should be cited in publications when applicable
	•	Publication decisions are made by the PI in consultation with contributors

⸻

12. Student and Alumni Policy
	•	Graduated members retain Read-only access
	•	Write or Maintain access is revoked after graduation unless extended
	•	All contributions remain permanently credited
	•	Alumni may be invited back as collaborators when appropriate

⸻

13. Code of Conduct

All members are expected to:
	•	Maintain professionalism and respect
	•	Provide constructive feedback
	•	Uphold academic integrity
	•	Avoid harassment or discrimination

Violations may result in removal from the organization.

⸻

14. Long-Term Sustainability Policy

This research unit GitHub organization is designed to:
	•	Survive personnel changes
	•	Support reproducible and transparent research
	•	Preserve institutional knowledge
	•	Enable future researchers to build upon past work

⸻

15. Acknowledgement

This guideline represents the collective commitment of the research unit
to excellence, integrity, and sustainable academic collaboration.

⸻

Last updated: December 2025
