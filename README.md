# JARVIS AI Assistant (Mark-LXXXV)

A sophisticated, low-latency AI assistant engineered to handle real-time voice interactions, system automation, and contextual multi-language workflows. Developed by **Sahil Raut**, this project showcases advanced capabilities in natural language processing (NLP), asynchronous task architectures, and hardware-level systems integration.

---

## 🚀 Core Features

### 🌐 1. Multilingual Intelligence
- **Seamless Switching:** Intuitively understands, translates, and responds across multiple languages including English, Japanese, and more.
- **Native Audio Processing:** Leverages next-generation multimodal streaming to preserve emotional inflection, tone, and pronunciation accuracy.

### 💻 2. System Control & File Management
- **OS Automation:** Interacts with the host machine to manage local files, directory structures, and system configurations securely.
- **Active Workspace Sync:** Tailored for IDE environments like VS Code to help manage active workspace pipelines.

### 🕸️ 3. Web Integration & Operations
- **Real-Time Web Search:** Dynamically fetches up-to-date information, answers queries, and interacts with APIs on the fly.
- **Browser Control:** Orchestrates headless or active browser workflows to automate repetitive web tasks.

### 🤖 4. Task Automation & Parallel Execution
- **Asynchronous Engine:** Utilizes Python's `asyncio` structure (`TaskGroup`) to handle concurrent microphone input, continuous speaker output, and deep backend calculations at the same time.
- **Resilient Pipelines:** Built with automated retry logic to catch session interruptions and reconnect without dropping your active state.

---

## 🛠️ Architecture & Technical Stack

- **Core SDK:** `google.genai` (Unified modern Google Gemini Client)
- **Primary Model:** `gemini-2.5-flash-native-audio-latest`
- **Network Protocol:** Low-latency Bidirectional WebSockets (`websockets`)
- **Concurrency:** Python `asyncio` Task Groups
- **Environment:** Python 3.11+

---

## 💾 Installation & Setup

### 1. Prerequisites
Ensure you have Python 3.11+ installed and added to your system environment variables.

### 2. Clone and Navigate
```bash
git clone [https://github.com/hackerskr76/Jarvis/main.git](https://github.com/hackerskr76/Jarvis/main.git)
cd Jarvis-main
