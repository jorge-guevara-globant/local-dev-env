# Vulcan local dev env

Install vagrant and virtualbox

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

Follow from `Installing Python 3.5.4`: https://smiledirectclub.atlassian.net/wiki/spaces/EN/pages/62881827/Getting+Started+on+OSX
