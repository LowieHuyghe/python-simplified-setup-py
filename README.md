# Easier Python Setup Script

An easier python setup script. Keep your `setup.py` organized with a simple ini-config-file.


## Installation

1. `cd` into your project directory
2. Copy the files in your Python project:

 ```bash
# Curl
curl https://raw.githubusercontent.com/LowieHuyghe/easier-python-setup-script/master/setup.py -o setup.py
curl https://raw.githubusercontent.com/LowieHuyghe/easier-python-setup-script/master/setup.config.ini -o setup.config.ini

# Wget
wget -O setup.py https://raw.githubusercontent.com/LowieHuyghe/easier-python-setup-script/master/setup.py
wget -O setup.config.ini https://raw.githubusercontent.com/LowieHuyghe/easier-python-setup-script/master/setup.config.ini
```
3. Change `setup.config.ini` to your likings
4. Debug the generated setup kwargs with:

 ```bash
python setup.py --debug
```


## Usage

You can use the setup.py as you normally would:
```bash
python setup.py test
```
