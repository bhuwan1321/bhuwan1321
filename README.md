# bhuwan1321

Student developer working on full-stack applications, machine learning, and DevSecOps tooling.
I build projects end to end: design, implementation, tests, CI and documentation.

## Focus

- **DevSecOps:** automated security scanning in CI, container and infrastructure-as-code checks, secrets detection
- **Backend and full-stack:** REST APIs, relational databases, React and Next.js front ends
- **Applied machine learning:** model training, evaluation and serving behind a web API
- **Local-first systems:** services that run on your own machine with no required cloud account

## Selected projects

### [aim-os](https://github.com/bhuwan1321/aim-os)
A personal AI memory system: persistent vector and relational memory, automatic research, voice interface and a web dashboard.
- Fourteen compose services coordinated over a Redis event bus; Qdrant for vectors, PostgreSQL for relational data, Ollama for local models
- Every port bound to localhost, cross-site writes refused, private-address blocking in the browser agent
- Automated test cycle covering contracts, data round trips, security, performance and chaos recovery
- Python, Docker, Redis, PostgreSQL, Qdrant, Ollama

### [vulnerability-scanning-pipeline](https://github.com/bhuwan1321/vulnerability-scanning-pipeline)
A team DevSecOps project that I extended into one repeatable workflow running seven open-source scanners: Semgrep, pip-audit, TruffleHog, Gitleaks, Trivy, Checkov and Bandit.
- The same script runs locally, in Docker and in GitHub Actions, with thresholds set in one config file
- SARIF upload to the Security tab, per-scan report artifacts and an in-app results API
- Found and fixed real findings in its own container image
- Python, Flask, Docker, GitHub Actions

### [task-manager](https://github.com/bhuwan1321/task-manager)
A full-stack task manager with due dates, overdue detection, filtering and a statistics dashboard.
- REST API on Express with parameterized PostgreSQL queries and server-side validation
- React and Vite front end; tested end to end against a real database
- React, Node.js, Express, PostgreSQL

### [engineer-dashboard](https://github.com/bhuwan1321/engineer-dashboard)
A personal dashboard for tracking fitness, DSA practice, academics and career tasks.
- Firestore security rules restrict every collection to the signed-in owner's documents
- Next.js, TypeScript, Firebase

### [ipl_score_predictor](https://github.com/bhuwan1321/ipl_score_predictor)
Predicts IPL first-innings scores and win probability with gradient boosting, trained on 278,000+ ball-by-ball records (2008 to 2025).
- Reported MAE of about 16 runs and R² of about 0.56 on held-out matches
- Flask API with input validation; dependency versions pinned to match the saved model
- Python, scikit-learn, Flask

## Skills

| Area | Tools |
|---|---|
| Languages | Python, JavaScript, TypeScript, Java, HTML, CSS |
| Back end | Node.js, Express, Flask, REST APIs, PostgreSQL, Redis |
| Front end | React, Next.js, Vite |
| DevOps and security | Docker, GitHub Actions, Semgrep, Trivy, Checkov, Gitleaks, Bandit |
| Data and ML | scikit-learn, pandas, NumPy, Qdrant, Ollama |

## Currently working on

- Expanding the scanning pipeline with more tests and stricter, triaged IaC checks
- Preparing AIM OS for open-source use: setup documentation, tests and a clean install path
