# AI-dependencies
Script for new environment preparation 

## Cập nhật hệ thống
```bash
sudo apt update && sudo apt upgrade -y
```

## NVIDIA drivers
- Kiểm tra card đồ họa NVIDIA:
```bash
lspci | grep -i nvidia
```
- Cài driver mới nhất từ NVIDIA:
```bash
sudo apt install nvidia-driver-5xx -y
```
- Kiểm tra driver đã hoạt động
```bash
nvidia-smi
```
## Cài đặt CUDA Toolkit
- Kiểm tra phiên bản mới nhất tại: [NVIDIA CUDA](https://developer.nvidia.com/cuda-downloads)
- Tải và cài đặt CUDA 12.8 cho Ubuntu x89_64:
```bash
wget https://developer.download.nvidia.com/compute/cuda/12.8.0/local_installers/cuda_12.8.0_570.86.10_linux.run
sudo sh cuda_12.8.0_570.86.10_linux.run
```
