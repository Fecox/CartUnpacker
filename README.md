# CartUnpacker

A development utility for **Picotron** that extracts `.p64` cartridges into organized project files, making them easier to inspect, edit, and maintain.

CartUnpacker was created to improve the workflow of developing games for Picotron by converting monolithic cartridge files into a structured project layout better suited for version control and collaborative development.

---

## Features

- 📦 Extract `.p64` cartridges into individual project files.
- 📂 Separate source code, graphics, sound effects, music, and assets.
- 🛠️ Generate a clean directory structure for easier navigation.
- 🔍 Simplify debugging and code inspection.
- 🌱 Improve compatibility with Git and other version control systems.
- ⚡ Streamline the Picotron development workflow.

---

## Why CartUnpacker?

Picotron cartridges store an entire project inside a single `.p64` file. While this is convenient for distribution, it makes version control, code review, and project organization significantly more difficult.

CartUnpacker bridges that gap by transforming a cartridge into a readable project structure that developers can work with using standard development tools.

---

## Use Cases

- Reverse engineering personal projects.
- Organizing large Picotron games.
- Version control with Git.
- Easier code reviews.
- Team collaboration.
- Learning from existing projects.

---

## Technologies

- Lua
- Picotron API
- File parsing
- Custom development tooling

---

## How It Works

1. Open a `.p64` cartridge.
2. Parse the cartridge contents.
3. Extract each resource into its corresponding file.
4. Generate a structured project directory ready for editing.

---

## Motivation

CartUnpacker was developed to solve a common workflow problem while creating games in Picotron.

Instead of editing large cartridge files directly, developers can work with individual source files, making projects easier to maintain, debug, and synchronize using Git.

---

## Learning Outcomes

This project involved working with:

- File parsing
- Custom data processing
- Tool development
- Automation
- Project organization
- Developer workflow optimization

---

## Future Improvements

Possible future features include:

- Repacking projects back into `.p64` cartridges.
- Incremental synchronization.
- Plugin support.
- Batch processing.
- Improved metadata handling.

---

## License

MIT License.
