# Quantization-on-MNIST-of-Tensorflow-Model
The quantization effects of Post-training quantization and Quantization aware training are compared

env:

python==3.6
tensorflow==2.4.0

pip uninstall -y tensorflow
pip install -q tf-nightly
pip install -q tensorflow-model-optimization

use TF Lite
int8 Quantization
Convert using integer-only quantization
