$ py --list

$ py --list-paths

$ py -m venv .test (creates python virtual env with base python version)

$ .\.test\Script\activate (activates python virtual env)

$ deactivate (deactivates virtual env)
$ rmdir /q /s .test (deletes directory .test q = quitly, s = recursively)
$ py -3.8 --version (refers the python version 3.8)
$ py -3.8 -m venv .test-env (creates python virtual env with python version 3.8)
$ pip install package_name==1.2.3
$ pip install package_name<=1.2
$ pip install package_name>1.2
$ pip install -r requirement.txt
$ pip freeze (shows the list of installed packages)
$ jupyter notebook . (open jupyter notebook in browser)
