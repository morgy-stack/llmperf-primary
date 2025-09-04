# llmperf-primary

A framework for load testing LLM APIs

## Built with

- Python (14 files)
- Shell (1 file)

## Getting started

```sh
pip install .
```

## Project structure

```
llmperf-primary/
    src/
        llmperf/
            ray_clients/
                __init__.py
                litellm_client.py
                openai_chat_completions_client.py
                sagemaker_client.py
                vertexai_client.py
            __init__.py
            common.py
            common_metrics.py
            models.py
            ray_llm_client.py
            requests_launcher.py
            sonnet.txt
            utils.py
    .gitignore
    analyze-token-benchmark-results.ipynb
    llm_correctness.py
    NOTICE.txt
    pre-commit.sh
    pyproject.toml
    requirements-dev.txt
    token_benchmark_ray.py
```
