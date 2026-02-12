# CI-CD-Pipeline-Monitor-Dashboard
-------
## Table of Contents
1. [CI/CD Pipeline Monitor & Dashboard](#project-1-cicd-pipeline-monitor--dashboard)
<img width="1589" height="1181" alt="image" src="https://github.com/user-attachments/assets/62d80d24-b514-4eb5-a73d-7569a84cde7c" />
---
### Description
A real-time monitoring system for CI/CD pipelines that tracks build status, deployment metrics, and generates visual reports. Supports multiple CI/CD platforms (Jenkins, GitLab CI, GitHub Actions).

### Features
- Real-time pipeline status monitoring
- Build success/failure rate analytics
- Deployment frequency tracking
- Interactive dashboard with charts
- Alert notifications for failures
- Historical trend analysis

### Tech Stack
- Python 3.8+
- Matplotlib/Plotly for visualizations
- Flask for dashboard
- SQLite for data storage

### Installation
```bash
pip install flask matplotlib pandas requests sqlite3
python cicd_monitor.py
```

### Usage
```python
# Configure your CI/CD endpoints
monitor = CICDMonitor()
monitor.add_pipeline("Jenkins", "http://jenkins.example.com")
monitor.start_monitoring()
```

### Output
Generates real-time dashboard showing:
- Pipeline success rates
- Build duration trends
- Deployment frequency graphs
- Failure analysis charts

---
