# Dockerイメージの整理

## 1. x86_64(GPU)向けのイメージ
### 1.1 D-FINEのTensorRT変換・推論する環境
[fuukeidaisuki/cuda12.3-ubuntu22.04-dfine](https://hub.docker.com/repository/docker/fuukeidaisuki/cuda12.3-ubuntu22.04-dfine/general)
```bash
docker push fuukeidaisuki/cuda12.3-ubuntu22.04-dfine:v1.0
```
### 1.2 MMdetectionのYOLOXで学習・推論する環境(mmdet3.x)
[fuukeidaisuki/mmdection-3.x](https://hub.docker.com/repository/docker/fuukeidaisuki/mmdection-3.x/general)
```bash
docker push fuukeidaisuki/mmdection-3.x:v1.1
```
### 1.3 YOLO-NASの学習・推論する環境(cuda-11.8, ubuntu22.04)
[fuukeidaisuki/cuda11.8-ubuntu22.04-yolo-nas](https://hub.docker.com/repository/docker/fuukeidaisuki/cuda11.8-ubuntu22.04-yolo-nas/general)
```bash
docker push fuukeidaisuki/cuda11.8-ubuntu22.04-yolo-nas:v1.1
```

### 1.4 YOLOXの学習・推論する環境(cuda-11.8, ubuntu22.04)
[fuukeidaisuki/cuda11.8-ubuntu22.04-yolox](https://hub.docker.com/repository/docker/fuukeidaisuki/cuda11.8-ubuntu22.04-yolox/general)
```bash
docker push fuukeidaisuki/cuda11.8-ubuntu22.04-yolox:v1.0
```

### 1.4 YOLOX-TRT変換・推論する環境
[fuukeidaisuki/server-cuda11.8-ubuntu22.04-yolox-trt](https://hub.docker.com/repository/docker/fuukeidaisuki/server-cuda11.8-ubuntu22.04-yolox-trt/general)
```bash
docker push fuukeidaisuki/server-cuda11.8-ubuntu22.04-yolox-trt:v1.0
```

## 2. x86_64(CPU)向けのイメージ
### 2.1 libtorchのテスト環境
[fuukeidaisuki/libtorch-dev-ubuntu22.04](https://hub.docker.com/repository/docker/fuukeidaisuki/libtorch-dev-ubuntu22.04/general)
```bash
docker push fuukeidaisuki/libtorch-dev-ubuntu22.04:cpu
```

## 3. Jetson向けのイメージ
### 3.1 JetsonでD-FINEのTensorRT変換・推論する環境(jetpack-r35.4.1)
[fuukeidaisuki/l4t-jetpack-r35.4.1-dfine-tensorrt](https://hub.docker.com/repository/docker/fuukeidaisuki/l4t-jetpack-r35.4.1-dfine-tensorrt/general)
```bash
docker push fuukeidaisuki/l4t-jetpack-r35.4.1-dfine-tensorrt:v1.0
```

### 3.2 JetsonでYOLO-NASのTensorRT変換・推論する環境(jetpack-r35.4.1)
[fuukeidaisuki/l4t-jetpack-r35.4.1-yolonas-tensorrt](https://hub.docker.com/repository/docker/fuukeidaisuki/l4t-jetpack-r35.4.1-yolonas-tensorrt/general)
```bash
docker push fuukeidaisuki/l4t-jetpack-r35.4.1-yolonas-tensorrt:v1.0
```

### 3.3 MMdetectionのYOLOXでTensorRT変換・推論する環境(jetpack-r35.4.1:mmdet3.x)
[fuukeidaisuki/mmdet3.x-yolox](https://hub.docker.com/repository/docker/fuukeidaisuki/mmdet3.x-yolox/general)
```bash
docker push fuukeidaisuki/mmdet3.x-yolox:l4t-jetpack-r35.4.1
```

### 3.4 JetsonでYOLO-NASのTensorRT変換・推論する環境(jetpack-r36.2.0)
[fuukeidaisuki/l4t-jetpack-r36.2.0-yolonas-tensorrt](https://hub.docker.com/repository/docker/fuukeidaisuki/l4t-jetpack-r36.2.0-yolonas-tensorrt/general)
```bash
docker push fuukeidaisuki/l4t-jetpack-r36.2.0-yolonas-tensorrt:v1.1
```

### 3.5 JetsonでYOLO-NASのONNX変換・推論する環境(jetpack-r36.2.0)
[fuukeidaisuki/l4t-jetpack-r36.2.0-yolonas-onnxruntme](https://hub.docker.com/repository/docker/fuukeidaisuki/l4t-jetpack-r36.2.0-yolonas-onnxruntme/general)
```bash
docker push fuukeidaisuki/l4t-jetpack-r36.2.0-yolonas-onnxruntme:v1.0
```

## 3.6 YOLOXのTRT変換・推論する環境(jetpack-r36.2.0)
[fuukeidaisuki/l4t-jetpack-r36.2.0-yolox-trt](https://hub.docker.com/repository/docker/fuukeidaisuki/l4t-jetpack-r36.2.0-yolox-trt/general)
```bash
docker push fuukeidaisuki/l4t-jetpack-r36.2.0-yolox-trt:v1.2
```
