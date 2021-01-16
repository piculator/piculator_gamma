# 在服务器上安装piculator-gamma

```bash
git clone --depth=1 -b main https://github.com/piculator/piculator_gamma
cd piculator_gamma
pip3 install virtualenv
virtualenv -p /bin/python3 venv
source venv/bin/activate
pip install -r requirements.txt
./start-gamma.sh
```
