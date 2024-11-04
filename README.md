# Hướng Dẫn Cài Đặt Python, Pytorch và ComfyUI

## 1. Python

**Phiên bản Python**: Nên sử dụng phiên bản 3.10 hoặc 3.11

## 2. Pytorch:
  ### 2.1. Phiên bản Pytorch: Nên sử dụng phiên bản mới nhất được cung cấp của pytorch
  ### 2.2. Cài đặt Pytorch:
  - **Build**: Chọn `Stable` (phiên bản ổn định) hoặc `Nightly` (bản thử nghiệm).
  - **Operating System**: Chọn hệ điều hành đang sử dụng (Linux, Windows, Mac).
  - **Package**: Chọn `pip` nếu dùng Python hoặc `conda` nếu dùng Anaconda.
  - **Compute Platform**: Chọn `CUDA` nếu có GPU NVIDIA hoặc `CPU` nếu không có.
  - **Sử dụng câu lệnh mà web cung cấp và dán vào cmd để download pytorch**:
  - **Nếu sử dụng GPU NVIDIA và chọn CUDA 11.8, dùng lệnh sau**:
    ```bash
    pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
     ```
### 3. Cài Đặt ComfyUI:
  #### 3.1 **Clone Repository ComfyUI từ GitHub**:
       ```bash
       git clone https://github.com/comfyanonymous/ComfyUI.git
       ```

  #### 3.2 Khởi Động ComfyUI
  
  - **Chạy ComfyUI**:
     - Mở thư mục ComfyUI, doublle click vào file run_nvidia_gpu (hoặc run_cpu nếu sử dụng cpu)
     - Hoặc: Trong cmd cd vào thư mục ComfyUI và gõ lệnh:
       ```bash
       run_nvidia_gpu
       ```
  - **Truy Cập Giao Diện**:
     - Mở trình duyệt và truy cập `http://localhost:8188`.

## 4. Cài đặt ComfyUI Manager (không bắt buộc):
  1. Truy cập trang GitHub của ComfyUI: [ComfyUI GitHub Repository](https://github.com/comfyanonymous/ComfyUI).
  2. Cd vào ComfyUI/custom_nodes dir trong terminal(cmd)
  3. Gõ lệnh:
     ```bash
       git clone https://github.com/ltdrdata/ComfyUI-Manager.git
     ```
  4. Restart ComfyUI
