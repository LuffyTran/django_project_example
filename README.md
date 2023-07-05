# Install poetry
```
sudo apt install python3.8-distutils
wget https://bootstrap.pypa.io/get-pip.py
python get_pip.py
python -m pip install -r requirentment
```

# Command Description
```
poetry install
```
```
poetry run python manage.py migrate
```
# Test 
```
poetry run flake8
```

```
poetry run test
```

# Bumpversion
Using 
```
bumpversion patch
```
for fix bug

```
bumpversion minor
```
for release new feature

```
bumpversion major
```
for big change

Push tags to remote repository
```
git push origin --tags
```
