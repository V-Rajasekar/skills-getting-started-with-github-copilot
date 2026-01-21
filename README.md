# Getting Started with GitHub Copilot

<img src="https://octodex.github.com/images/Professortocat_v2.png" align="right" height="200px" />

Hey V-Rajasekar!

Mona here. I'm done preparing your exercise. Hope you enjoy! 💚

Remember, it's self-paced so feel free to take a break! ☕️

[![](https://img.shields.io/badge/Go%20to%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/V-Rajasekar/skills-getting-started-with-github-copilot/issues/1)

---

## Running the Application

First, install the dependencies:

```bash
pip install -r requirements.txt
```

To run the FastAPI server:

```bash
python -m uvicorn src.app:app --reload
```

The application will be available at `http://localhost:8000`

## Running the Tests

The project includes comprehensive pytest tests for all API endpoints. To run the tests:

```bash
pytest tests/ -v
```

To run tests with detailed output:

```bash
pytest tests/ -v --tb=short
```

To run a specific test file:

```bash
pytest tests/test_app.py -v
```

To run a specific test class:

```bash
pytest tests/test_app.py::TestSignupForActivity -v
```

To run a specific test:

```bash
pytest tests/test_app.py::TestSignupForActivity::test_signup_success -v
```

---

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

