# Vulcan local dev env


## Ubuntu 1404

Clone the Vulcan repository

```
git clone git@github.com:CamelotVG/scc-api.git
```

Only the first time:

```
apt-get install python3-venv
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

If you already installed pip requirements

```
source venv/bin/activate
```

Run vagrant

```
vagrant up
```
