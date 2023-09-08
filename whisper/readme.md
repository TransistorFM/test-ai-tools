This is the output of [whisper.cpp](https://github.com/ggerganov/whisper.cpp) using the "small" model, and the command line below.

Whisper is free; Castopod has added [installation instructions here](https://blog.castopod.org/install-whisper-cpp-on-your-mac-in-5mn-and-transcribe-all-your-podcasts-for-free/).

```
./main -m models/ggml-small.bin --output-vtt --output-srt --max-len 32 --output-txt -f ~/tmp/tempinput.wav -of ~/tmp/$1
```