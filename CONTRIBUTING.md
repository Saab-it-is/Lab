# Contributing to Lab

Thank you for your interest in contributing to this lab repository!

## How to Add Experiments

1. **Choose the right directory:**
   - `experiments/` - For small, focused experiments (single files or small projects)
   - `projects/` - For larger proof-of-concept projects with multiple components
   - `examples/` - For tutorial-style code examples

2. **Create a new directory for your experiment:**
   ```bash
   mkdir experiments/my-experiment
   cd experiments/my-experiment
   ```

3. **Add a README:**
   - Every experiment or project should have a README.md explaining:
     - What the experiment demonstrates
     - Technologies used
     - How to run it
     - Key learnings or observations

4. **Keep dependencies isolated:**
   - Use virtual environments for Python projects
   - Use separate package.json for Node.js projects
   - Document all dependencies clearly

## Guidelines

- **Be descriptive:** Use clear names for directories and files
- **Document everything:** Add comments and README files
- **Keep it organized:** Follow the repository structure
- **Test your code:** Ensure experiments run as documented
- **Clean up:** Remove unnecessary files before committing

## Example Experiment Structure

```
experiments/python-decorators/
├── README.md
├── requirements.txt (if needed)
├── example.py
└── notes.md
```

## Questions?

Feel free to open an issue for any questions or suggestions!
