# Visualize - AI files

Files the Visualize app (YBK AUDIO, https://ybkaudio.com) downloads the first time its stem separation
(VOCAL / INST) or STEMS colours are used. Nothing here needs to be downloaded by hand.

- onnxruntime.dll - Microsoft ONNX Runtime 1.30.0 (MIT License, https://github.com/microsoft/onnxruntime)
- vocals.onnx, accompaniment.onnx - Deezer Spleeter 2-stem model (MIT License, https://github.com/deezer/spleeter),
  converted to ONNX by sherpa-onnx (Apache-2.0, https://github.com/k2-fsa/sherpa-onnx)
- vocals4.onnx, drums.onnx, bass.onnx, other.onnx - Deezer Spleeter 4-stem model (MIT License), ONNX from
  https://github.com/practicesession222/PracticeSession-assets (spleeter-models-v1.0)