# Contributing to CVEN 5833

Thank you for your interest in contributing to the CVEN 5833 course materials!

## For Teaching Assistants

### Adding New Materials

1. **Create a new branch** for your changes:
   ```bash
   git checkout -b feature/add-lecture-X
   ```

2. **Follow the existing structure**:
   - Lectures go in `lectures/`
   - Notebooks go in `notebooks/`
   - Assignments go in `assignments/`

3. **Use consistent naming conventions**:
   - Lectures: `XX_topic_name/`
   - Notebooks: `XX_topic_name.ipynb`
   - Assignments: `assignment_XX/`

4. **Test your materials**:
   - Run all notebook cells to ensure they execute without errors
   - Verify that required datasets are accessible
   - Check that dependencies are listed in `requirements.txt`

5. **Submit a pull request**:
   - Provide a clear description of the new materials
   - Tag the course instructor for review

### Updating Existing Materials

1. Create a branch for your updates
2. Make minimal, focused changes
3. Document what was changed and why
4. Submit a pull request for review

## For Students

### Reporting Issues

If you find errors in the course materials:

1. **Check if the issue already exists** in the Issues tab
2. **Create a new issue** with:
   - Clear description of the problem
   - Steps to reproduce
   - Expected vs. actual behavior
   - Screenshots if applicable

### Suggesting Improvements

We welcome suggestions for improving the course materials:

1. Open an issue describing your suggestion
2. Explain why the improvement would be beneficial
3. If possible, provide examples or references

## Code Style Guidelines

### Python Code

- Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/) style guide
- Use meaningful variable names
- Add docstrings to functions and classes
- Keep functions focused and concise

### Jupyter Notebooks

- Include markdown cells explaining concepts
- Break code into logical cells
- Clear outputs before committing (use `Cell > All Output > Clear`)
- Include comments for complex operations

### Documentation

- Use clear, concise language
- Include examples where appropriate
- Update README files when adding new directories
- Check for typos and grammar errors

## Adding Dependencies

If you need to add a new Python package:

1. Add it to `requirements.txt` with version constraint
2. Document why the package is needed
3. Verify it's compatible with existing packages

## Commit Messages

Write clear, descriptive commit messages:

- Use present tense ("Add feature" not "Added feature")
- Be specific about what changed
- Reference issue numbers when applicable

Examples:
```
Add lecture 5 on deep learning fundamentals
Fix typo in assignment 2 instructions
Update requirements.txt with xarray>=0.19.0
```

## Review Process

All contributions will be reviewed by the course instructor before merging:

1. Code quality and correctness
2. Consistency with existing materials
3. Educational value
4. Documentation completeness

## Questions?

If you have questions about contributing, please:
- Contact the course instructor
- Ask in the course forum
- Open an issue for discussion

## License

By contributing to this repository, you agree that your contributions will be licensed under the MIT License.
