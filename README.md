# django-cicd-pipeline
Automated CI/CD pipeline for a Django app using Jenkins and GitLab CI, deploying to AWS EC2 with automated testing.


django-cicd-pipeline/
├── app/                    # Django app code
│   ├── manage.py
│   ├── requirements.txt    # flask==2.0.1, gunicorn==20.1.0, werkzeug==2.0.3
│   └── app.py              # Simple Django/Flask app
├── .gitlab-ci.yml          # GitLab CI config
├── Jenkinsfile             # Jenkins pipeline script
├── Dockerfile              # Docker image for app
└── README.md               # Pipeline setup, badges, AWS deployment guide
