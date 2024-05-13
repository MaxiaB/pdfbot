
<h3>Welcome to OffboardingGPT v0.1</h3>

To get started:

```sh
cd /downloads/pdfbot
```

1. Install `virtualenv`:
    ```sh
    pip3 install virtualenv
    ```

2. Create a virtual environment using `pyenv`:
    ```sh
    pyenv virtualenv 3.10.6 pdfbot
    ```

3. Set the local Python version to the virtual environment:
    ```sh
    pyenv local pdfbot
    ```

4. Install dependencies:
    ```sh
    pip install -r requirements.txt
    ```

5. Create local .env File:
    ```sh
    mv .env.example .env
    ```

6. Add `OPENAI_API_KEY` in the `.env` file at the root directory. You can get a free API key at [OpenAI](https://platform.openai.com).

7. To run your app locally:
    ```sh
    streamlit run app.py
    ```
