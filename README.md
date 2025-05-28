# MariTheon

> **Core Intelligence Engine for Developer Assistance**

**MariTheon** is a modular, Java-based developer assistant inspired by the name "Maria".  
It combines software engineering structure with intelligent components to help you code faster, cleaner, and with style.

---

## 🎯 Goals

- Modular, extensible architecture (Java)
- Local Swing-based UI for easy use
- Smart developer agents (e.g., code generation, review, docs)
- Future LLM integration (ChatGPT, Claude, Gemini, local models)
- Optional plugin-based evolution
- Personal memory and context support

---

## 🛠 Tech Stack

- **Language:** Java 17+
- **Build Tool:** Gradle
- **UI:** Java Swing
- **HTTP:** OkHttp (for API communication)
- **Future AI:** OpenAI / LLM API clients

---

## 📁 Project Structure

```
MariTheon/
├── build.gradle
├── settings.gradle
└── src/main/java/com/maritheon/
    ├── MariTheonApp.java          # Main application with UI
    ├── core/                      # Core engine logic
    ├── agent/                     # Modular AI/dev helper agents
    ├── memory/                    # Config, memory, state
    └── ui/                        # Swing components
```

---

## 🚀 Getting Started

### 🔧 Clone the Repo

```bash
git clone https://github.com/yourusername/MariTheon.git
cd MariTheon
```

### 🛠 Build and Run

```bash
./gradlew build
./gradlew run
```

> You need JDK 17+ installed.

---

## 🤖 Planned Features

- [x] Java-based modular architecture
- [ ] Swing UI (simple input/output)
- [ ] Chat agent with GPT-4 via OpenAI API
- [ ] Code analysis agent
- [ ] Notes/memory panel for ongoing context
- [ ] Multi-agent support (Claude, Gemini, etc.)

---

## 🧠 About the Name

> "MariTheon" is a tribute to Maria Almpani, my mom, resting in piece — envisioned as a digital presence of clarity, memory, and structure in the world of software engineering.

---

## 📄 License

MIT License.  
**Created with love and logic.**
