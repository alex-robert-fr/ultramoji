# ultramoji

✨ **ultramoji** — An ultra-light, minimalist alternative to gitmoji, written in pure C with no external dependencies.

---

## 📦 About

**ultramoji** is a work-in-progress project.
The goal is to build a command-line tool that adds standardized emojis to Git commit messages, inspired by [gitmoji](https://gitmoji.dev), but:

* written in **pure C**,
* with **zero external dependencies** (only the C standard library),
* and designed to be **modular**, so you only include the emojis relevant to your project.

---

## 🚀 Planned Features

✅ List of emojis and their descriptions

✅ Search emojis by keyword

✅ Interactive CLI interface

✅ Configuration file to customize which emojis are available

✅ Zero external dependencies

---

## ⚠️ Project Status

🚧 **In development**
Currently, no features are implemented yet.
The first commits will focus on setting up:

* Project structure
* Command-line argument handling
* Loading a minimal configuration file
* Simple terminal output

Contributions and ideas are already welcome!

---

## 🔧 Installation (coming soon)

Once the project is functional, the expected installation steps will be:

```bash
git clone https://github.com/alex-robert-fr/ultramoji.git
make
```

Expected prerequisites:

* A C compiler (`gcc` or `clang`)
* `make`

---

## 📜 Roadmap

* [ ] Project setup
* [ ] Basic CLI (`list`, `search`, `commit`)
* [ ] Custom configuration support (`.ultramoji.json`)
* [ ] Documentation and examples
* [ ] Stable release

---

## 🤝 Contributing

Even though the project is still empty, you can:

* **open issues** to suggest ideas, features, or potential pitfalls,
* **prepare PRs** for the architecture, docs, or tests,
* **share your input** on priorities and roadmap.
