# HeadlessFlow Voice Repository

This repository hosts the Text-to-Speech (TTS) voice models used by the **HeadlessFlow** app.

## Purpose
The app requires offline TTS models in a specific structure (ZIP archive containing `tokens.txt`, `model.onnx`, and `espeak-ng-data`). These files are served via GitHub Releases to allow the app to download them on demand.

## Models
The models are converted from the official **Sherpa Onnx** (Piper) releases:
- [k2-fsa/sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx)

## License
Models are subject to their original licenses (typically CC0 or MIT depending on the underlying dataset).
