# chas-ff-hackaton
Chas FFs hackaton

# First Pipeline Challenge

![CI/CD Pipeline](https://github.com/MarcusGustafsson28/first-pipeline/workflows/CI%2FCD%20Pipeline/badge.svg)

Live deployment: [https://dashboard.render.com/web/srv-d65f4gp5pdvs73d8oj5g/deploys/dep-d65f647gi27c73bsr2hg?r=2026-02-10%4008%3A56%3A52~2026-02-10%4008%3A59%3A07]

## About
Week 4 Boiler Room Hackathon - Building a complete CI/CD pipeline.

## Architecture
```
Code Push → GitHub Actions → Tests → Docker Build → Trivy Scan → Deploy
```

## Status
✓ All tests passing
✓ Security scan complete
✓ Deployed to production
