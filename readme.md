# AI Engineer Chat with Multi-Agent, Image, and Voice Support

This project is an advanced AI chat system that incorporates multi-agent functionality, image processing, and voice support. It's built upon the work of Doriandarko and has been modified to use AI/MLAPI with Meta-Llama models.

## Features

- Multi-agent AI chat system
- Image processing capabilities
- Voice input support
- Autonomous mode for continuous operation
- File management and code execution within a virtual environment
- Web search integration using Tavily API
- Conversation history management and saving

## Acknowledgements

- Original project creator: Doriandarko
- Special thanks to Pietro Schirano for inspiration and guidance
   https://github.com/Doriandarko/claude-engineer
- Modified by Vicmuchina  to use AI/MLAPI with Meta-Llama models

## Prerequisites

- Python 3.8 or higher
- pip (Python package installer)
- Virtual environment tool (e.g., venv)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/vicmuchina/claude_engineer_with_llama.git
   cd claude_engineer_with_llama
   ```

2. Create a virtual environment:
   ```
   python -m venv venv
   ```

3. Activate the virtual environment:
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS and Linux:
     ```
     source venv/bin/activate
     ```

4. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

5. Create a `.env` file in the project root directory and add your API keys:
   ```
   API_KEY=your_aimlapi_key_here
   TAVILY_API_KEY=your_tavily_api_key_here
   ```

## Usage

1. Ensure your virtual environment is activated.

2. Run the main script:
   ```
   python main.py
   ```

3. Follow the on-screen instructions to interact with the AI chat system.

### Available Commands

- Type 'exit' to end the conversation.
- Type 'image' to include an image in your message.
- Type 'voice' to enter voice input mode.
- Type 'automode [number]' to enter Autonomous mode with a specific number of iterations.
- Type 'reset' to clear the conversation history.
- Type 'save chat' to save the conversation to a Markdown file.

## Project Structure

- `main.py`: The main script containing the AI chat system logic.
- `requirements.txt`: List of Python packages required for the project.
- `.env`: Configuration file for API keys (not included in the repository).
- `.gitignore`: Specifies intentionally untracked files to ignore.

## Contributing

Contributions to improve the project are welcome. Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature.
3. Make your changes and commit them with clear, descriptive messages.
4. Push your changes to your fork.
5. Submit a pull request with a clear description of your changes.

## License

[Include your chosen license here]

## Disclaimer

This project uses AI models and APIs that may have usage limits or costs associated with them. Please be aware of the terms of service for AI/MLAPI and Tavily API when using this project.