# aider: AI Pair Programmer in your terminal

[https://aider.chat](https://aider.chat)

Aider is an AI pair programmer that helps you code in your terminal. It uses large language models to edit code in your local git repository. This repository is built to install and run aider easily on any linux distribution. It also includes a sample .env file for configuration.

## Installation

### Prerequisites

*   Python 3.7 or higher.
*   Tested on Linux ubuntu 24.04.

### Install aider using `pip` and `venv` (recommended)

1.  **Clone the aider repository:**
    ```bash
    git clone https://github.com/kadavilrahul/aider_on_linux.git && cd aider_on_linux
    ```
2.  **Change sample_env to .env**

    ```bash
    mv sample_env .env
    ```
3. Add credentials to .env
    ```bash
    OPENROUTER_API_KEY=your_api_key
    ``` 
4.  **Create a virtual environment:**
    ```bash
    bash install.sh
    ```
5.  **Run aider:**
    ```bash
    bash run.sh
    ```
### Verify Installation

After installation, verify that aider is installed correctly by checking the version:


## Features

*   **Adds AI to your existing workflow:**  Use aider with your existing git repo, code, and tools.
*   **Works in your terminal:** No need to leave your familiar terminal environment.
*   **Edits code in place:** Aider directly modifies your local files.
*   **Understands code context:** Aider uses git to understand your project's structure and code history.
*   **Supports multiple models:**  Easily switch between different language models like GPT-4o, Claude 3, and open-source models.
*   **Voice-to-code:**  Use your voice to interact with aider and generate code.
*   **Web chat integration:**  Copy and paste code context to use aider with web-based LLMs.
*   **Built-in linting and testing:** Automatically lint and test your code after AI edits.
*   **In-chat commands:**  Control aider and git directly from the chat interface.
*   **Configuration and customization:**  Extensive options to tailor aider to your needs.

## Documentation

Detailed documentation is available at [https://aider.chat/docs/](https://aider.chat/docs/).

Key documentation files in this repository include:

*   `analytics.md`:  Details about usage analytics.
*   `chat_modes.md`:  Information on different chat modes (code, architect, ask, help).
*   `copy_paste_with_web_chat.md`:  Documentation for using aider with web-based LLM interfaces.
*   `fix_and_commit.md`:  Details on linting, testing, and committing changes.
*   `git_settings.md`:  Configuration options related to git integration.
*   `images_and_web_pages.md`:  Using images and web pages as context in chat.
*   `important_commands.md`:  Quick reference for essential commands.
*   `inchat_commands.md`:  Comprehensive list of all in-chat slash commands.
*   `linting_and_testing.md`:  In-depth guide to linting and testing features.
*   `modes.md`:  Explanation of command-line modes and options.
*   `other_settings.md`:  Documentation for various other settings and options.
*   `tips.md`:  Tips and best practices for using aider effectively.
*   `upgrading.md`:  Instructions for upgrading aider to newer versions.
*   `voice.md`:  Configuration for voice input features.
*   `voice_to_code.md`:  Guide to using voice-to-code functionality.


