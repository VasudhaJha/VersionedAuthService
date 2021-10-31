# VersionedAuthService

## Setup

1. Install pyenv

```bash
curl https://pyenv.run | bash
```

2. Update bash profile by adding
the following to ~/.bashrc:

```bash
export PATH="$HOME/.pyenv/bin:$PATH"
eval "$(pyenv init --path)"
eval "$(pyenv virtualenv-init -)"
```

3. Install Python

```bash
pyenv install -v 3.10.0
pyenv global 3.10.0
```

4. Create virtual environment

```bash
pyenv virtualenv .venv
pyenv activate .venv
```

5. Install requirements

```bash
pip install -r requirements.txt
```

6. Run VersionedAuthService

```bash
python app.py
```
