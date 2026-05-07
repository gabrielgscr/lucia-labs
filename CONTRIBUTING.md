# Contributing to lucia-labs

Thanks for contributing examples to Lucia Labs.

## Scope

This repository is focused on practical Lucia language examples that help users learn syntax, language features, and common patterns.

## Example Naming Convention

Naming rules depend on where the example is added:

1. In `compiler-examples/`:

```text
NN_topic_name.lucia
```

- `NN` is a two-digit sequence number (for example: 00, 01, 02).
- `topic_name` must be short, descriptive, and in snake_case.
- Use English names for consistency across the repository.

Examples:

- `00_features.lucia`
- `14_hello_world.lucia`
- `16_syntax_multiple_errors.lucia`

2. New standalone example:

Create a new folder in snake_case with a representative name, and place example files inside that folder.

```text
my_new_example_case/
  main.lucia
  helpers.lucia
```

Use explicit internal names like `main.lucia`, `helpers.lucia`, `models.lucia` when needed.

## Authoring Guidelines

- Keep examples small and focused on one concept whenever possible.
- Prefer readable variable and function names.
- Add short comments only when logic is not obvious.
- Avoid adding unrelated changes in the same contribution.

## Local Validation

Before opening a PR, validate your example with Lucia CLI.

Run:

```bash
lucia run compiler-examples/14_hello_world.lucia
lucia compile compiler-examples/00_features.lucia
```

If your example targets JavaScript, also validate with:

```bash
lucia run compiler-examples/14_hello_world.lucia --target js
```

## Pull Request Checklist

- [ ] File and folder names follow the naming convention.
- [ ] Example runs successfully with `lucia run`.
- [ ] Example compiles successfully with `lucia compile`.
- [ ] README references were updated if paths changed.
- [ ] Changes are scoped only to examples and related docs.
