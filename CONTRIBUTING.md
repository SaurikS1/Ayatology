# Contributing to Scientific Quran Evidence

Thank you for your interest in contributing to the Scientific Quran Evidence documentation. This guide will help you understand how to contribute content and collaborate effectively.

## Getting Started

1. Fork the repository
2. Clone your fork locally
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the site locally:
   ```bash
   mkdocs serve
   ```

## Content Guidelines

### File Structure
- Place new articles in the appropriate subdirectory under `docs/`
- Use lowercase with hyphens for filenames (e.g., `water-cycle.md`)
- Update `mkdocs.yml` if adding new sections

### Content Format
- Use Markdown formatting
- Include a clear title and introduction
- Structure content with clear headings (h2, h3)
- Reference Quranic verses with proper citation
- Include scientific references and sources
- Use proper formatting for quotes and citations

### Writing Style
- Be objective and scientific
- Provide clear evidence and references
- Use simple, clear language
- Include diagrams or images where helpful
- Maintain academic integrity

## Workflow

1. Create a new branch for your content:
   ```bash
   git checkout -b content/topic-name
   ```

2. Add your content and test locally

3. Commit your changes:
   ```bash
   git add .
   git commit -m "Add: Description of your content"
   ```

4. Push to your fork:
   ```bash
   git push origin content/topic-name
   ```

5. Create a Pull Request

## Review Process

1. Your content will be reviewed for:
   - Scientific accuracy
   - Proper citations
   - Writing quality
   - Technical correctness

2. Address any feedback in the Pull Request

3. Once approved, your content will be merged and automatically deployed

## Publishing Updates

The site automatically deploys when changes are merged to the main branch. To publish updates:

1. Make sure your content is in the correct directory
2. Update navigation in `mkdocs.yml` if needed
3. Submit a Pull Request
4. After approval and merge, changes will be live in minutes

## Need Help?

- Open an issue for questions
- Join discussions in the existing issues
- Check the documentation for technical guidance

Thank you for contributing to this important project!
