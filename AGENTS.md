# Agent Instructions

- Do not run local builds, Gradle tasks, or commands that may download dependencies in this repository.
- Do not run `./gradlew`, `gradle`, Android Studio builds, or local compile/test commands unless the user explicitly overrides this rule in the same turn.
- Use GitHub workflows for build and compile verification.
- If verification is needed, prepare or trigger the appropriate GitHub workflow instead of building locally.
