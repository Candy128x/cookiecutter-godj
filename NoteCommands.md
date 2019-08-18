# Commands
	
---
- description..
- => pwd


---
- Create a virtualenv for your project and activate it:

- => mkvirtualenv venv
- => workon venv


---
- => pip3 install django


---
- => pip install cookiecutter
- op:
```
(venv) ashish@ashish-Vostro-3478:cookiecutter-godj$ pip install cookiecutter
DEPRECATION: Python 2.7 will reach the end of its life on January 1st, 2020. Please upgrade your Python as Python 2.7 won't be maintained after that date. A future version of pip will drop support for Python 2.7. More details about Python 2 support in pip, can be found at https://pip.pypa.io/en/latest/development/release-process/#python-2-support
Collecting cookiecutter
  Using cached https://files.pythonhosted.org/packages/16/99/1ca3a75978270288354f419e9166666801cf7e7d8df984de44a7d5d8b8d0/cookiecutter-1.6.0-py2.py3-none-any.whl
Collecting whichcraft>=0.4.0 (from cookiecutter)
  Using cached https://files.pythonhosted.org/packages/19/31/b35bfa8bd4a5b539a4a1cef56f0701c93387b9a644572bf2d31440351324/whichcraft-0.6.0-py2.py3-none-any.whl
Collecting binaryornot>=0.2.0 (from cookiecutter)
  Using cached https://files.pythonhosted.org/packages/24/7e/f7b6f453e6481d1e233540262ccbfcf89adcd43606f44a028d7f5fae5eb2/binaryornot-0.4.4-py2.py3-none-any.whl
Collecting jinja2>=2.7 (from cookiecutter)
  Using cached https://files.pythonhosted.org/packages/1d/e7/fd8b501e7a6dfe492a433deb7b9d833d39ca74916fa8bc63dd1a4947a671/Jinja2-2.10.1-py2.py3-none-any.whl
Collecting requests>=2.18.0 (from cookiecutter)
  Using cached https://files.pythonhosted.org/packages/51/bd/23c926cd341ea6b7dd0b2a00aba99ae0f828be89d72b2190f27c11d4b7fb/requests-2.22.0-py2.py3-none-any.whl
Collecting future>=0.15.2 (from cookiecutter)
  Using cached https://files.pythonhosted.org/packages/90/52/e20466b85000a181e1e144fd8305caf2cf475e2f9674e797b222f8105f5f/future-0.17.1.tar.gz
Collecting poyo>=0.1.0 (from cookiecutter)
  Using cached https://files.pythonhosted.org/packages/42/50/0b0820601bde2eda403f47b9a4a1f270098ed0dd4c00c443d883164bdccc/poyo-0.5.0-py2.py3-none-any.whl
Collecting jinja2-time>=0.1.0 (from cookiecutter)
  Using cached https://files.pythonhosted.org/packages/6a/a1/d44fa38306ffa34a7e1af09632b158e13ec89670ce491f8a15af3ebcb4e4/jinja2_time-0.2.0-py2.py3-none-any.whl
Collecting click>=5.0 (from cookiecutter)
  Using cached https://files.pythonhosted.org/packages/fa/37/45185cb5abbc30d7257104c434fe0b07e5a195a6847506c074527aa599ec/Click-7.0-py2.py3-none-any.whl
Collecting chardet>=3.0.2 (from binaryornot>=0.2.0->cookiecutter)
  Using cached https://files.pythonhosted.org/packages/bc/a9/01ffebfb562e4274b6487b4bb1ddec7ca55ec7510b22e4c51f14098443b8/chardet-3.0.4-py2.py3-none-any.whl
Collecting MarkupSafe>=0.23 (from jinja2>=2.7->cookiecutter)
  Using cached https://files.pythonhosted.org/packages/fb/40/f3adb7cf24a8012813c5edb20329eb22d5d8e2a0ecf73d21d6b85865da11/MarkupSafe-1.1.1-cp27-cp27mu-manylinux1_x86_64.whl
Collecting urllib3!=1.25.0,!=1.25.1,<1.26,>=1.21.1 (from requests>=2.18.0->cookiecutter)
  Using cached https://files.pythonhosted.org/packages/e6/60/247f23a7121ae632d62811ba7f273d0e58972d75e58a94d329d51550a47d/urllib3-1.25.3-py2.py3-none-any.whl
Collecting certifi>=2017.4.17 (from requests>=2.18.0->cookiecutter)
  Using cached https://files.pythonhosted.org/packages/69/1b/b853c7a9d4f6a6d00749e94eb6f3a041e342a885b87340b79c1ef73e3a78/certifi-2019.6.16-py2.py3-none-any.whl
Collecting idna<2.9,>=2.5 (from requests>=2.18.0->cookiecutter)
  Using cached https://files.pythonhosted.org/packages/14/2c/cd551d81dbe15200be1cf41cd03869a46fe7226e7450af7a6545bfc474c9/idna-2.8-py2.py3-none-any.whl
Collecting arrow (from jinja2-time>=0.1.0->cookiecutter)
  Using cached https://files.pythonhosted.org/packages/4f/c6/32df2c68e02e2d6b4457223fa499634edabb2d4ff74f00087ffff49b4be4/arrow-0.14.5-py2.py3-none-any.whl
Collecting backports.functools-lru-cache>=1.2.1; python_version == "2.7" (from arrow->jinja2-time>=0.1.0->cookiecutter)
  Downloading https://files.pythonhosted.org/packages/03/8e/2424c0e65c4a066e28f539364deee49b6451f8fcd4f718fefa50cc3dcf48/backports.functools_lru_cache-1.5-py2.py3-none-any.whl
Collecting python-dateutil (from arrow->jinja2-time>=0.1.0->cookiecutter)
  Using cached https://files.pythonhosted.org/packages/41/17/c62faccbfbd163c7f57f3844689e3a78bae1f403648a6afb1d0866d87fbb/python_dateutil-2.8.0-py2.py3-none-any.whl
Collecting six>=1.5 (from python-dateutil->arrow->jinja2-time>=0.1.0->cookiecutter)
  Using cached https://files.pythonhosted.org/packages/73/fb/00a976f728d0d1fecfe898238ce23f502a721c0ac0ecfedb80e0d88c64e9/six-1.12.0-py2.py3-none-any.whl
Building wheels for collected packages: future
  Building wheel for future (setup.py) ... done
  Created wheel for future: filename=future-0.17.1-cp27-none-any.whl size=500236 sha256=bc37d04904a9c9cf32bd123a5ff6d78af197db3c4f4a0ee97004c750ca4c7131
  Stored in directory: /home/ashish/.cache/pip/wheels/0c/61/d2/d6b7317325828fbb39ee6ad559dbe4664d0896da4721bf379e
Successfully built future
Installing collected packages: whichcraft, chardet, binaryornot, MarkupSafe, jinja2, urllib3, certifi, idna, requests, future, poyo, backports.functools-lru-cache, six, python-dateutil, arrow, jinja2-time, click, cookiecutter
Successfully installed MarkupSafe-1.1.1 arrow-0.14.5 backports.functools-lru-cache-1.5 binaryornot-0.4.4 certifi-2019.6.16 chardet-3.0.4 click-7.0 cookiecutter-1.6.0 future-0.17.1 idna-2.8 jinja2-2.10.1 jinja2-time-0.2.0 poyo-0.5.0 python-dateutil-2.8.0 requests-2.22.0 six-1.12.0 urllib3-1.25.3 whichcraft-0.6.0

```


---
- => cookiecutter https://github.com/audreyr/cookiecutter-pypackage.git
- op:
```
(venv) ashish@ashish-Vostro-3478:cookiecutter-godj$ cookiecutter https://github.com/audreyr/cookiecutter-pypackage.git
full_name [Audrey Roy Greenfeld]: Ashish Develoepr
email [audreyr@example.com]: sondagarashish@g.com            
github_username [audreyr]: candy128x
project_name [Python Boilerplate]: PBR
project_slug [pbr]: br
project_short_description [Python Boilerplate contains all the boilerplate you need to create a Python package.]: PBR desc..
pypi_username [candy128x]: 
version [0.1.0]: 
use_pytest [n]: 
use_pypi_deployment_with_travis [y]: 
add_pyup_badge [n]: 
Select command_line_interface:
1 - Click
2 - No command-line interface
Choose from 1, 2 (1, 2) [1]: 
create_author_file [y]: y
Select open_source_license:
1 - MIT license
2 - BSD license
3 - ISC license
4 - Apache Software License 2.0
5 - GNU General Public License v3
6 - Not open source
Choose from 1, 2, 3, 4, 5, 6 (1, 2, 3, 4, 5, 6) [1]: 6
```


---
# Make own cookiecutter template

- => mkdir template1

- => vim template1/cookiecutter.json
- add:
```
{
  "repo_name": "reponame",
  "full_name": "Ashish Developer",
  "email": "sondagarashish@g.com",
  "config": "wasup"
}
```

- => mkdir template1/{{cookiecutter.repo_name}}

- => vim template1/\{\{cookiecutter.repo_name\}\}/file.txt
- add:
```
Name: {{cookiecutter.full_name}}
Email: {{cookiecutter.email}}
Config: {{cookiecutter.config}}
```

---
### Run cookiecutter 

- => cookiecutter template1/
```
(venv) ashish@ashish-Vostro-3478:cookiecutter-godj$ cookiecutter template1/
repo_name [reponame]: myapp
full_name [Ashish Developer]: 
email [ashishsondagar@g.com]: 
config [wasup]: I am a config variable
```


---
## Create template2 dir

- => mkdir template2
- => cd template2/

- => vim cookiecutter.json
- add:
```
{
  "project_name": "project_name is the title of the project.",
  "repo_name": "repo_name is used for describing the directory structure.",
  "author_name": "Ashish Developer",
  "email": "Ashish Sondagar",
  "description": "A short description of the project."
}
```


---
### Create dj project inside template2

- => django-admin.py startproject demoproj
- => cd demoproj/

- => vim manage.py
`os.environ.setdefault('DJANGO_SETTINGS_MODULE', 'demoproj.settings')`
to 
`os.environ.setdefault('DJANGO_SETTINGS_MODULE', '{{cookiecutter.repo_name}}.settings')`


- => vim wsgi.py & urls.py, settings.py
- Replace from
`demoproj`
to
`{{cookiecutter.repo_name}}`


- => ls
(venv) ashish@ashish-Vostro-3478:demoproj$ ls
demoproj  manage.py


- => mv demoproj/ {{cookiecutter.repo_name}}/
(venv) ashish@ashish-Vostro-3478:demoproj$ mv demoproj/ {{cookiecutter.repo_name}}/


- => ls
(venv) ashish@ashish-Vostro-3478:demoproj$ ls
{{cookiecutter.repo_name}}  manage.py
(venv) ashish@ashish-Vostro-3478:demoproj$ cd ..
(venv) ashish@ashish-Vostro-3478:template2$ mv demoproj/ {{cookiecutter.repo_name}}/
(venv) ashish@ashish-Vostro-3478:template2$ ls
cookiecutter.json  {{cookiecutter.repo_name}}


- => Run `template2`
(venv) ashish@ashish-Vostro-3478:cookiecutter-godj$ cookiecutter template2
project_name [project_name is the title of the project.]: My Awesome app
repo_name [repo_name is used for describing the directory structure.]: milldolide
author_name [Ashish Developer]: Ashish
email [Ashish Sondagar]: sondagarashish@gm.com
description [A short description of the project.]: Million dollar project to make one million dollars


(venv) ashish@ashish-Vostro-3478:cookiecutter-godj$ ls
br  gitPushU.bash  milldolide  myapp  NoteCommands.md  Notes3.md  template1  template2


(venv) ashish@ashish-Vostro-3478:cookiecutter-godj$ cd milldolide/

(venv) ashish@ashish-Vostro-3478:milldolide$ ls
manage.py  milldolide


- => python3 manage.py runserver