# 创建名为vllm的虚拟环境，指定Python版本为3.12
conda create -n vllm python=3.12 -y

# 激活虚拟环境
conda activate vllm

# 安装vllm库
pip install vllm