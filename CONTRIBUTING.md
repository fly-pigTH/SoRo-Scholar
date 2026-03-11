# Contributing to SoRo-Scholar

We welcome contributions from researchers, students, and enthusiasts worldwide.

## Adding a Paper

1. Fork the repo and create a new branch.
2. Find the appropriate topic file in `/papers`.
3. Add the paper in the correct year section:
   ```
   [Venue Year] [Paper Title](DOI-URL) (Authors)
   ```
4. Submit a Pull Request.

## Adding a Researcher

1. Find the appropriate country folder in `/researchers`.
2. Create `firstname-lastname.md` using this template:
   ```markdown
   # Full Name
   **Affiliation:** University, Department
   **Lab:** [Lab Name](lab-url)
   ## Research Interests
   Brief description.
   ## Selected Publications
   - [Venue Year] Paper Title (Authors)
   ```
3. Add the researcher to the table in `README.md`.
4. Submit a Pull Request.

## Guidelines

- **Accuracy first.** Double-check titles, names, venues, and years.
- **Use DOI links** when possible.
- **Keep formatting consistent** with existing files.
- **One PR per contribution type.**
