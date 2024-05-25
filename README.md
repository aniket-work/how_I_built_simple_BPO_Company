# how_I_built_small_recruitment_company_w_AI_Agents
how_I_built_small_recruitment_company_w_AI_Agents

## Setting Up how_I_built_small_recruitment_company_w_AI_Agents Environment
To set up the `how_I_built_small_recruitment_company_w_AI_Agents` environment, follow these steps:

1. Create a virtual environment using Python's built-in `venv` module:

    ```bash
    python -m venv how_I_built_small_recruitment_company_w_AI_Agents
    ```

2. Activate the virtual environment:

    - On Windows:

        ```bash
        how_I_built_small_recruitment_company_w_AI_Agents\Scripts\activate
        ```

    - On Unix or MacOS:

        ```bash
        source how_I_built_small_recruitment_company_w_AI_Agents/bin/activate
        ```

3. Install dependencies 
   ```bash
   pip install -r requirements.txt
   ```
   
4. install ollama from https://ollama.com/download

5. install llama3 in ollama
   ```bash
   ollama run llama3:8b          
   ```
6. setup ollama into dify
   6.1 click on "model provider", search ollama
   6.2 add model name and url as  http://host.docker.internal:11434  (this is if you running dify in docker, and ollma on host m/c) 



