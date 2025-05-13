# llama-stack

Local Ollama
```
INFERENCE_MODEL=qwen3:8b uv run --with llama-stack llama stack build --template ollama --image-type venv --run
```

vLLM-Remote
```
INFERENCE_MODEL=my-model VLLM_URL=https://my-model-new-vllm.apps.ragm-azure-pool-6fcqf.azure.rh-ods.com/v1 VLLM_TLS_VERIFY=false uv run --with llama-stack llama stack build --template remote-vllm --image-type venv --run
```
