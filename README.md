# Two-Bee-Desktop-AI-Assistant.
AI assistant with voice control, smart web search, and desktop automation. Two-Bee listens, browses, and handles system tasks to keep your workflow light and fast.
🐝 Two-Bee — AI Desktop Assistant

Two-Bee is a lightweight, voice-driven AI assistant that hums along your desktop, helping you search, browse, and control your system with ease. Built with Python, Eel, and your custom engine, it blends web tech and automation into a smooth companion experience.

✨ Features

🎤 Voice Recognition
Listen-first design for hands-free commands and conversation.

🌐 Web Surfing & Smart Search
Opens queries, fetches info, and navigates the browser for you.

🖥️ Desktop Control
Launch apps, manage windows, and trigger system tasks.

🔎 Quick Commands
Integrated command engine for fast, flexible actions.

💻 Eel-based UI
A lightweight front-end served through Chrome in app mode.

📁 Project Structure
/engine
    /features        # Core assistant abilities
    /command         # Command parsing & execution
/www
    index.html       # Web UI served via Eel
main.py              # Entry point for launching Two-Bee

🚀 Getting Started
1. Install Dependencies
pip install eel
# plus any dependencies used inside engine.features and engine.command

2. Run the Assistant
python main.py


Two-Bee will open in Chrome as a standalone app and start listening for commands.

⚙️ How It Works

The assistant loads a web interface using Eel.

Chrome is launched in app mode:
chrome.exe --app="http://localhost:8000/index.html".

Voice and system features are handled through Python modules inside engine/.

The assistant starts with a little intro sound — just enough to let you know it’s awake.

🛠️ Technologies Used

Python 3

Eel (Python ↔ Browser bridge)

Chrome App Mode

Custom Engine Modules for voice, search, and control

🌱 Future Improvements (Optional)

More natural conversational abilities

Custom trigger word (“Hey Two-Bee”)

Local model integration

UI themes

Plugin-style command system
