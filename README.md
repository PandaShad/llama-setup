# Play with LLaMa cpp on your post

## Get the code 

```bash
git clone https://github.com/ggerganov/llama.cpp
cd llama.cpp
```
## Build
- Using ```make```:
    - ```make```
- Using ```Cmake```:
```bash
mkdir buid
cd build
cmake ..
cmake --build . --config Release
```

## Prepare Data & Run

If you want to use the original LLaMa model weights you'll need to find it by yourself as it is not officialy provided by facebook (you can find it on reddit)

### Alternative using Alpaca
1. First, download the ggml Alpaca model into the ./models folder
    - [Alpaca model](https://huggingface.co/Sosaka/Alpaca-native-4bit-ggml/blob/main/ggml-alpaca-7b-q4.bin)
2. Run the main tool like this:
```bash
./examples/alpaca.sh
```