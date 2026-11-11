Built by .github/workflows/mywords-ios-web.yaml from mywords/v2.0.1-export-ort @ 942bdd78b8ac7d74c4cc8749c42174c0c4bf247b.

sherpa_onnx_ios and sherpa_onnx_web with the onnxruntime C API exported
(OrtGetApiBase; wasmTable on the web). Use as dependency_overrides:

    dependency_overrides:
      sherpa_onnx_ios:
        git: {url: https://github.com/lvxduck/sherpa-onnx.git, ref: mywords-dist, path: sherpa_onnx_ios}
      sherpa_onnx_web:
        git: {url: https://github.com/lvxduck/sherpa-onnx.git, ref: mywords-dist, path: sherpa_onnx_web}
