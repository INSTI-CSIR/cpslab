# MkDocs Documentation with Material Theme

This repository contains a documentation project built using [MkDocs](https://www.mkdocs.org/) and the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme. Follow the steps below to set up the project and contribute changes.

---

## Getting Started

### Prerequisites
Ensure you have the following installed on your system:
- [Python 3.6+](https://www.python.org/)
- [pip](https://pip.pypa.io/en/stable/)
- [Git](https://git-scm.com/)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the development server:
   ```bash
   mkdocs serve
   ```
or if your port 8000 is in use

```bash
mkdocs serve -a 127.0.0.1:8001
```
   
   Open your browser and navigate to `http://127.0.0.1:8000` to view the documentation locally.

---

## How to Contribute

1. Create a new branch for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. Make edits to the documentation files in the `docs/` folder.

3. Test your changes locally:
   ```bash
   mkdocs serve
   ```

4. Commit and push your changes:
   ```bash
   git add .
   git commit -m "Describe your changes"
   git push origin feature/your-feature-name
   ```

5. Open a pull request to the `master` branch.

---

## Deployment Workflow
The repository owner will handle deployments to the `gh-pages` branch:
1. Once a pull request is reviewed and approved, it will be merged into the `master` branch.
2. The owner will run the following command to deploy the changes:
   ```bash
   mkdocs gh-deploy
   ```
3. The documentation will be live on the configured GitHub Pages URL.

---

## Dependencies
The project uses the following dependencies:
- MkDocs
- Material for MkDocs theme

These are specified in `requirements.txt`:
```text
mkdocs
mkdocs-material
```

---

## Additional Resources
- [MkDocs Documentation](https://www.mkdocs.org/)
- [Material for MkDocs Documentation](https://squidfunk.github.io/mkdocs-material/)
