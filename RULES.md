# Rules for Contributing and Versioning

## Forked Projects
- All projects forked from this repository must have their changes committed back to the original project.

## Contributing Changes
- When contributing, ensure that your changes are committed to the branch corresponding to the current version of the project.
- Do **not** make changes directly to the `main` branch.

## Branch Naming and Versioning
- Contributions should be made in a branch named `Vm`, where `m` is the version number.
- For small updates:
  - Do **not** change the version number.
  - Commit directly to the existing `Vm` branch.
- For major updates or significant changes:
  - Increment the version number following the format `Vm.x`, where:
    - `m` is the branch's numeric version (e.g., 1, 2, 3, etc.)
    - `x` is a periodic value indicating the update iteration (e.g., 0, 1, 2, etc.)
  - Create or update the branch named `Vm.x` accordingly.

### Examples:
- For initial release or major update: `V1`, `V2`, `V3`
- For a small updates: `V1.1`, `V1.2`, `V2.1`, etc.

## License
- This project is licensed under the GNU GPLv3 License. See the `LICENSE` file for more details.

## General Guidelines
- Always assign clear and descriptive commit messages.
- Ensure your code passes all tests before submitting a pull request.
- Follow the project's coding standards and best practices.

---

Thank you for contributing to the project!
