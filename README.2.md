```bash
python3 -m venv venv
source ./venv/bin/activate
./venv/bin/python -m pip install --upgrade pip
pip install wheel
pip install imagen-pytorch
# pip install --pre "torch>1.13.0.dev20220610" "torchvision>0.14.0.dev20220609" torchaudio --extra-index-url https://download.pytorch.org/whl/nightly/cpu
pip install --pre "torch=torch-1.13.0.dev20220619" "torchvision=torchvision-0.14.0.dev20220618" torchaudio --extra-index-url https://download.pytorch.org/whl/nightly/cpu

pip install jupyter kornia ema_pytorch
```