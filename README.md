# loom-models

loom 앱이 실행 중에 내려받는 모델 파일을 배포하는 저장소입니다.
모델 파일은 저장소에 커밋하지 않고 Release 첨부 파일로만 올립니다.

## 파일

| 모델 | Release 태그 | 파일 | 크기 (바이트) | SHA-256 |
|---|---|---|---|---|
| Qwen3.5 2B (Q5_K_M) | `qwen3.5-2b-q5_k_m` | `Qwen3.5-2B-Q5_K_M.gguf` | 1,411,121,184 | `eb9619e010111f8efd4ded286b3539d75e56e9029d379baa591b53a7ddec6999` |

- 원본: [Qwen/Qwen3.5-2B](https://huggingface.co/Qwen/Qwen3.5-2B)의 BF16 GGUF([unsloth/Qwen3.5-2B-GGUF](https://huggingface.co/unsloth/Qwen3.5-2B-GGUF), revision `f6d5376`)를 llama.cpp `b11429`로 Q5_K_M 양자화했습니다.
- 앱은 내려받은 파일의 크기와 SHA-256이 위 값과 같을 때만 사용합니다. 파일을 바꿀 때는 새 태그로 올리고 앱의 값도 함께 바꿉니다.

## 라이선스

Qwen3.5 2B 모델은 Apache License 2.0으로 배포됩니다. 전문은 [LICENSE-Qwen3.5-2B.txt](LICENSE-Qwen3.5-2B.txt)에 있습니다.
