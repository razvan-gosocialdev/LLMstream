### Instalation

- Get Python 3.11.4 with pip
https://www.python.org/downloads/

- Get the visual studio compiler: Check: Python development workload + the Native development tools option
https://visualstudio.microsoft.com/free-developer-offers/

- Get CUDA 12.2 update 1
https://developer.nvidia.com/cuda-downloads

- Download the LAMA2 model (llama-2-7b-chat.ggmlv3.q4_0.bin) from:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main

- Install pytorch with cuda support
```console
pip install numpy
```
```console
pip install langchain
```
```console
pip install sentence_transformers
```
```console
pip install simpleaudio
```

- Upgrade setup tools
```console
pip install --upgrade setuptools
```

- Install torch with CUDA support
```console
pip install --force-reinstall --no-cache-dir torch --index-url https://download.pytorch.org/whl/cu118
```

- Install llama-cpp-python
```console
set CMAKE_ARGS="-DLLAMA_CUBLAS=on" && set FORCE_CMAKE=1 && pip install --verbose --force-reinstall --no-cache-dir llama-cpp-python==0.1.77
```
