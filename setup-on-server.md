# 在服务器上安装piculator-gamma

```bash
git clone --depth=1 -b main https://github.com/piculator/piculator_gamma
cd piculator_gamma
pip3 install virtualenv
virtualenv -p /bin/python3 venv
source venv/bin/activate
pip install -r requirements.txt
chmod +x start-gamma.sh
./start-gamma.sh
```

注意: 请手动修改 app/settings.py

```python
ALLOWED_HOSTS = [
    '127.0.0.1',
    'localhost',
    '.sympygamma.com',
    '.sympy.org',
    '.appspot.com',
    '.kxxt.tech' # 将这里改为你的域名
]
```

