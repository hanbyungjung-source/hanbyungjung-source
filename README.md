제한된 연산·메모리 자원 안에서 **정확도를 지키며 성능을 끌어내는 SW**를 만듭니다.

## Projects

| 저장소 | 요약 | 기술 |
|---|---|---|
| [dual-gpu-llm-optimization](https://github.com/hanbyungjung-source/dual-gpu-llm-optimization) | 구형 RX 580 + RTX 5050(각 8GB)으로 27B 멀티모달 LLM 구동. 이종 GPU 배치, GCN Vulkan 커널 수정, 동적 가중치 재배치로 응답 시간 **약 24% 단축**, FP64 참조 대비 수치 검증 | C++, GLSL, CUDA, Vulkan, llama.cpp |
| [hahi-small-object-detection](https://github.com/hanbyungjung-source/hahi-small-object-detection) | 석사 논문. 가중 커널 밀도추정 기반 슬라이싱 + 동적 패킹으로 고해상도 소형 객체 AP **+46.9%** (vs Patch Packing), VRAM 224MB·40.1ms | Python, PyTorch, YOLOv8 |
| [stockcast](https://github.com/hanbyungjung-source/stockcast) | 91개 변수 기반 시장 예측 웹 서비스. 규제 회귀·칼만 필터·HRP, Oracle Cloud(Ubuntu·RHEL) 직접 운영 — [stockcast.info](https://stockcast.info) | Java, Spring Boot, Vue 3, MySQL |
| [local-desk-agent](https://github.com/hanbyungjung-source/local-desk-agent) | 로컬 LLM/외부 API 기반 Windows 데스크톱 작업 에이전트. 도구 승인, 코드 검색, 자원 감시 | Python, Tkinter |
| [dit-lora-training](https://github.com/hanbyungjung-source/dit-lora-training) | 8GB GPU에서 DiT 모델 LoRA/DoRA 학습. NF4·FP8 기저 가중치, FlashAttention 3. WSL(RTX 5050)·Azure(A10) | Python, PyTorch |

## Skills

- **Languages**: C/C++, C#, Java, Python, JavaScript, GLSL, CUDA
- **Systems**: Vulkan/CUDA 커널 최적화, 실시간 센서 데이터 처리(MAVLink), 임베디드(STM32, FPGA)
- **Infra**: Ubuntu, RHEL, Docker, Kubernetes, Jenkins, 폐쇄망 GitLab·Nexus
- **Build**: CMake, Ninja, LLVM-MinGW Clang
