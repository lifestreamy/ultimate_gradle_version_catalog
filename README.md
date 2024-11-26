## A pre-populated libs.versions.toml that can be used in Android and Kotlin Multiplatform Gradle projects
- The file is pre-populated with commonly used versions, plugins and libraries
- Plugins and dependencies for standard included builds (`buildSrc`, `build-logic`, etc.) are present as well
- It is specifically structured for easier comprehension and the versions are tested for compatibility in a real project 
- Feel free to open pull requests to add new useful entries or correct the existing ones ([Contributions](#Contributions))
- The file is lightweight, and the unused deps do not slow the project down

## Recommended tools and libs (optional)
 - [lifestreamy/compose_android_template](https://github.com/lifestreamy/compose_android_template) - my multi-modular project template for Android Compose projects that utilizes this version catalog 
 - [littlerobots/version-catalog-update-plugin](https://github.com/littlerobots/version-catalog-update-plugin) - a Gradle plugin for updating all the versions inside your `libs.versions.toml` at once
 - [jitpack.io](https://jitpack.io) - for adding dependencies on github repositories

## More information on versions and compatibility
 - [Compose Multiplatform Compatibility and versions](https://www.jetbrains.com/help/kotlin-multiplatform-dev/compose-compatibility-and-versioning.html#kotlin-compatibility)

## TODO & Ideas
 - Add automatic tests for versions compatibility with Github Actions
 - (?) Create separate version catalogs in this same repository to separate entirely different stacks and avoid conflicts

# Contributions
 Are always welcome! Create a pull request, open an issue, speak up in discussions, etc.

## Simple guidelines
 - Be polite, please
 - Don't be afraid to share your ideas!
 - Maintain clear and consistent structure and formatting across the whole file (files), make it readable and easily extendable
 - Suggest small corrections in issues or discussions first
 - You are free to do whatever you want with the code, considering the CC0 license
 - Mentioning this repo or me would be appreciated but is not required

---
 
Let's make this the biggest collection of versions in the universe!

-- Tim K.
