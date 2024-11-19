# Local-AI-Ollama-WebUI

## Setting Up Your Own AI Engine

### Prerequisites
1. Ensure you have Windows 10 version 1903 or later, or Windows 11.
2. Check your Windows version by pressing Windows key + R, typing "winver", and hitting Enter.

### Installing WSL 2
1. Open PowerShell as administrator.
2. Run the command: `wsl --install`
3. Download and install the WSL2 Linux kernel update package from Microsoft's website.
4. Set WSL 2 as the default version with the command: `wsl --set-default-version 2`

### Installing Ubuntu
1. Install Ubuntu from the Microsoft Store or use PowerShell command: `wsl --install -d Ubuntu`
2. Launch Ubuntu from the Start menu and set up your user account and password.

### Installing Ollama
1. Open the Ubuntu terminal.
2. Run the command: `curl -fsSL https://ollama.com/install.sh | sh`
3. Start Ollama by running: `ollama serve`

### Installing and Running a Model
1. Open a new terminal window.
2. Pull the Llama 2 model: `ollama pull llama2:latest`
3. List installed models: `ollama list`
4. Run the model: `ollama run llama2:latest`

### Setting Up Open Web UI
1. Install Docker: `sudo snap install docker`
2. Run the Open Web UI container (use the command provided in the video description)
3. Access the web interface by navigating to `localhost:3000` in your browser.
4. Create an admin account on first launch.

### Using Open Web UI
1. Select a model from the list of available models.
2. Start interacting with the AI through the chat interface.
3. Explore customization options to adjust model parameters and behavior.

Refer this video https://www.youtube.com/watch?v=DYhC7nFRL5I
