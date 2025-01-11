

# python-docker


python-docker-app/
├── app.py              # Python script
├── Dockerfile          # Dockerfile for building the Docker image
├── .github/
│   └── workflows/
│       └── ci-cd.yml   # GitHub Actions CI/CD workflow file
├── requirements.txt    # Python dependencies (if required)
├── argo-events/
│   ├── eventsource-github.yaml   # EventSource for GitHub webhook
│   └── sensor-github-push.yaml   # Sensor for triggering Argo workflow
