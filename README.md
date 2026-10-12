# Python Project Template

## Usage

Create a new project with this template:

```bash
uvx copier copy https://github.com/XomniaAI/python-project-template.git <path>
```

Or using SSH:

```bash
uvx copier copy git@github.com:XomniaAI/python-project-template.git <path>
```

Replace `<path>` with your desired project directory.

## Development

Run `uvx pre-commit install` once. It installs a gitleaks hook that scans
staged changes for secrets on every commit.
