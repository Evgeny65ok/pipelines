# 🚀 Pipelines

> Коллекция **CI/CD пайплайнов на GitHub Actions** для разных языков программирования.
> Учебный проект: примеры автоматизации сборки, тестирования, линтинга и Docker-сборки.

![CI](https://img.shields.io/badge/CI-GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)
![Languages](https://img.shields.io/badge/languages-7-success)
![Docker](https://img.shields.io/badge/Docker-ready-2496ED?logo=docker&logoColor=white)

---

## 📚 Список пайплайнов

| # | Язык / Стек | Что делает | Ссылка |
|---|-------------|------------|--------|
| 1 | 📦 **Node.js** | REST API, ESLint, Jest, Docker | [→](https://github.com/Evgeny65ok/pipelines-nodejs) |
| 2 | 🐍 **Python** | flake8, pytest (matrix 3.9–3.12), Docker | [→](https://github.com/Evgeny65ok/pipelines-python) |
| 3 | 🐹 **Go** | go vet, тесты с покрытием, Docker | [→](https://github.com/Evgeny65ok/pipelines-go) |
| 4 | ⚙️ **C++** | CMake, Google Test, clang-format, Docker | [→](https://github.com/Evgeny65ok/pipelines-cpp) |
| 5 | 🦀 **Rust (утилита)** | clippy, fmt, cargo test | [→](https://github.com/Evgeny65ok/pipelines-rust) |
| 6 | 🐘 **PHP** | PHP lint, PHPUnit, Docker | [→](https://github.com/Evgeny65ok/pipelines-php) |
| 7 | ☕ **Java** | Maven, JUnit 5, multi-stage Docker | [→](https://github.com/Evgeny65ok/hello-java) |
| 8 | 🦀 **Rust (CI #1)** | clippy, fmt, cargo test, multi-stage Docker | [→](https://github.com/Evgeny65ok/my-rust-app) |

---

## 📊 Статусы пайплайнов

| Пайплайн | Статус |
|----------|--------|
| 📦 Node.js | ![NodeJS](https://github.com/Evgeny65ok/pipelines-nodejs/actions/workflows/ci.yml/badge.svg) |
| 🐍 Python | ![Python](https://github.com/Evgeny65ok/pipelines-python/actions/workflows/ci.yml/badge.svg) |
| 🐹 Go | ![Go](https://github.com/Evgeny65ok/pipelines-go/actions/workflows/ci.yml/badge.svg) |
| ⚙️ C++ | ![C++](https://github.com/Evgeny65ok/pipelines-cpp/actions/workflows/ci.yml/badge.svg) |
| 🦀 Rust (утилита) | ![Rust](https://github.com/Evgeny65ok/pipelines-rust/actions/workflows/ci.yml/badge.svg) |
| 🐘 PHP | ![PHP](https://github.com/Evgeny65ok/pipelines-php/actions/workflows/ci.yml/badge.svg) |
| ☕ Java | ![Java](https://github.com/Evgeny65ok/hello-java/actions/workflows/ci.yml/badge.svg) |
| 🦀 Rust (CI #1) | ![Rust](https://github.com/Evgeny65ok/my-rust-app/actions/workflows/rust-ci.yml/badge.svg) |

---

## ⚙️ Что демонстрирует каждый пайплайн

| Язык | Lint | Test | Docker |
|------|------|------|--------|
| Node.js | ESLint | Jest | ✅ |
| Python | flake8 | pytest | ✅ |
| Go | go vet | go test | ✅ |
| C++ | clang-format | Google Test | ✅ |
| Rust (утилита) | clippy + fmt | cargo test | ✅ |
| PHP | php -l | PHPUnit | ✅ |
| Java | Maven | JUnit 5 | ✅ |
| Rust (CI #1) | clippy + fmt | cargo test | ✅ |

---

## 🏗️ Стек

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)

---

## 📂 Структура

Каждый пайплайн — **отдельный публичный репозиторий** со своим `.github/workflows/`:
