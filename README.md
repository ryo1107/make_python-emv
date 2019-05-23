input

```
sudo su -
yum update -y
yum upgrade -y
yum install git -y
git clone https://github.com/pyenv/pyenv.git ~/.pyenv
echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.profile
echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.profile
echo -e 'if command -v pyenv 1>/dev/null 2>&1; then\n  eval "$(pyenv init -)"\nfi' >> ~/.profile
source ~/.profile
which pyenv
```

output

```
/home/USERNAME/.pyenv/bin/pyenv
```

input

```
yum install gcc zlib-devel bzip2 bzip2-devel readline readline-devel sqlite sqlite-devel openssl openssl-devel -y
pyenv install --list
```

output

```
we can install python list
```

input

```
pyenv install 3.6.3
pyenv global 3.6.3
pip install --upgrade pip
```
