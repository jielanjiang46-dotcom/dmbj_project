# dmbj_project
## 青铜门小笔记
盗墓笔记同人小网站

# 1. 克隆项目
git clone https://github.com/Lyra/dmbj_project.git
cd dmbj_project

# 2.创建虚拟环境
本项目使用 Conda 管理依赖：

conda create -n dp_env python=3.11
conda activate dp_env
pip install -r requirements.txt

# 3.初始化项目
python manage.py migrate

# 4.启动开发服务器
python manage.py runserver