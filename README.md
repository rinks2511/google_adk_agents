# google_adk_agents
exploring agents via google agent development kit

## Setup Steps

1.  **Create the virtual environment**:
    Using `uv`, create and activate a virtual environment.
    ```bash
    uv venv
    source .venv/bin/activate
    ```

2.  **Install the SDK**:
    Install the `google-adk` package.
    ```bash
    uv pip install google-adk
    ```

3.  **Create the Agent**:
    Initialize the agent repository.
    ```bash
    adk create my_agent
    ```

4.  **Configure Environment**:
    Set up the `GEMINI_API_KEY` in the `.env` file.

5.  **Build the Agent**:
    Add tools and customize the agent logic in `agent.py`.
