# 워크플로우 모델 경로 분석 보고서

**워크플로우 파일:** `260204_MiracleCreationStudio_Master_Optimized.json`  
**ComfyUI 루트 경로:** `D:\ComfyUI\ComfyUI`

본 보고서는 해당 워크플로우에서 참조하거나 사용 중인 주요 모델들의 실제 절대 경로를 분석한 결과입니다.

---

### 1. SeedVR2 모델 (비디오 업스케일 및 DiT)
*   **메인 DiT 모델:**  
    `D:\ComfyUI\ComfyUI\models\SEEDVR2\seedvr2_ema_3b_fp16.safetensors`
*   **VAE 모델:**  
    `D:\ComfyUI\ComfyUI\models\SEEDVR2\ema_vae_fp16.safetensors`

### 2. SAM2 모델 (비디오 마스킹)
*   **SAM2 체크포인트:**  
    `D:\ComfyUI\ComfyUI\models\sam2\sam2.1_hiera_large.pt`  
    *(대체 경로: `D:\ComfyUI\ComfyUI\models\sams\sam2.1_hiera_large.pt`)*

### 3. FILM 모델 (프레임 보간)
*   **FILM 체크포인트:**  
    `D:\ComfyUI\ComfyUI\custom_nodes\comfyui-frame-interpolation\ckpts\film\film_net_fp32.pt`

### 4. 기타 관련 경로 및 체크포인트
*   **Stable Video Diffusion (SVD):**  
    `D:\ComfyUI\ComfyUI\models\checkpoints\stabilityai\stable-video-diffusion-img2vid-xt`
*   **VideoMaMa 관련:**  
    `D:\ComfyUI\ComfyUI\models\checkpoints\VideoMaMa`

---
*작성일: 2026년 3월 16일*
