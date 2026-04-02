# 1.Install Python
# 2.create virtul environment & activate
~~~
# create virtual environment mlx_env
python3 -m venv mlx_env

# Activate virtual environment
source mlx_env/bin/activate
~~~

# 3.Install mlx-lm in virtual environment
~~~
pip install -U mlx-lm
~~~

# 4.Install models
~~~
# There are mlx-lm community in huggingface where providing AI models for mlx-lm specifically
# Pick your model with command below to start the mlx-lm server, it will download the model automatically.
python -m mlx_lm.server --model mlx-community/Qwen3.5-27B-Claude-4.6-Opus-Distilled-MLX-4bit --port 8080
~~~
