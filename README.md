# Wednesday's Wicked Adventures

Repo for DevOps Project Management Assignment Group 3

**Horror Park Booking System** - A booking platform for horror theme parks.


## Quick Start

```bash
cd flask_app/src/main
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r ../requirements.txt
flask --app app run
```

## Contributing

1. Create feature branch: `git checkout -b feature/SCRUM-XX-description`
2. Make changes and commit
3. Create PR to `UAT` branch
4. After UAT approval, merge to `main`

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

## Documentation

Full project documentation is available in the [docs/](docs/) folder and is automatically built on every PR.

- [Project Overview](docs/index.md)
- [Local Setup Guide](docs/setup-local.md)
- [CI/CD Pipeline](docs/pipeline.md)
- [Testing & Quality](docs/testing-quality.md)
- [Security](docs/security.md)
- [Admin Guide](docs/admin.md)

## Tech Stack

- Python 3.9.7+
- Flask
- SQLAlchemy
- Flask-Login
- SQLite (dev) / MySQL (prod)
