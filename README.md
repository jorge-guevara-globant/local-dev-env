# Vulcan local dev env

Install vagrant and virtualbox

* https://www.vagrantup.com/downloads.html
* https://www.virtualbox.org/wiki/Downloads

## Ubuntu 1804

Clone the Vulcan repository

```
git clone git@github.com:CamelotVG/scc-api.git
```

Only the first time:

Ubuntu

```
apt-get install python3-venv
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Windows:

Download Python

* https://www.python.org/downloads/windows/

```
py -m pip install --user virtualenv
py -m venv env
.\env\Scripts\activate
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
