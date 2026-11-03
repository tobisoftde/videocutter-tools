# videocutter-tools

Prebuilt helper programs for Video KI Cutter.

## whisper.cpp with Vulkan (Windows x64)

The official [whisper.cpp](https://github.com/ggml-org/whisper.cpp) releases ship Windows builds only for CPU and
NVIDIA (CUDA). This repo builds whisper.cpp with `GGML_VULKAN=ON`, so speech recognition runs on AMD Radeon and
Intel GPUs as well.

- Build: Actions → "whisper.cpp Vulkan build" → Run workflow (input: whisper.cpp tag)
- Result: release `whisper-vulkan-<tag>` with `whisper-bin-win-vulkan-x64.zip`

whisper.cpp is MIT licensed; its license file is included in every zip as `LICENSE-whisper.cpp.txt`.
