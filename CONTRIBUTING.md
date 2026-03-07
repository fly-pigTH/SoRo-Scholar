# Contributing to SoRo-Scholar

Thank you for your interest in contributing! SoRo-Scholar is a community-driven project, and we welcome contributions from researchers, students, and enthusiasts worldwide.

## How to Contribute

### Adding a Paper

1. Fork the repository and create a new branch.
2. Find the appropriate topic file in the `/papers` directory.
3. Add the paper entry in the correct year section using this format:

```
[Venue Year] [Paper Title](URL) (Authors)
```

For example:
```
[Nature 2015] [Design, fabrication and control of soft robots](https://doi.org/10.1038/nature14543) (Daniela Rus, Michael T. Tolley)
```

4. If the paper does not fit an existing topic, open an issue to discuss adding a new category.
5. Submit a Pull Request.

### Adding a Researcher

1. Find the appropriate country folder in `/researchers`.
2. Create a new markdown file named `firstname-lastname.md`.
3. Use this template:

```markdown
# Full Name

**Affiliation:** University, Department
**Lab:** [Lab Name](lab-url)

## Research Interests
Brief description of research focus areas.

## Key Contributions
- Notable contribution 1
- Notable contribution 2

## Selected Publications
- [Venue Year] Paper Title (Authors)
```

4. Add the researcher to the table in `README.md`.
5. Submit a Pull Request.

### Correcting Information

If you spot incorrect information (wrong year, misspelled name, broken link), please either:
- Open an **Issue** describing the error, or
- Submit a **Pull Request** with the fix directly.

### Suggesting New Categories

Open an **Issue** with the title "New Category: [Name]" and describe what the category would cover and why it is distinct from existing ones.

## Guidelines

- **Accuracy first.** Double-check paper titles, author names, venues, and years.
- **Use DOI links** when possible (e.g., `https://doi.org/10.xxxx/xxxxx`). They are stable and publisher-independent.
- **Keep formatting consistent.** Follow the existing style in each file.
- **One PR per contribution type.** Don't mix paper additions with researcher profiles in the same PR.
- **English only.** All content should be in English.

## Code of Conduct

Be respectful and constructive. We are building a resource for the entire soft robotics community. Contributions are reviewed on their merit, regardless of the contributor's background or affiliation.
