# Django-Oscar Problem
This is what I get when navigating to http://localhost:8000/
```
ValueError at /

dictionary update sequence element #0 has length 1; 2 is required

Request Method: 	GET
Request URL: 	http://localhost:8000/
Django Version: 	3.1.6
Exception Type: 	ValueError
Exception Value:

dictionary update sequence element #0 has length 1; 2 is required

Exception Location: 	/var/work/django/oscar/lib/python3.8/site-packages/django/urls/resolvers.py, line 358, in resolve
Python Executable: 	/var/work/django/oscar/bin/python
Python Version: 	3.8.6
Python Path:

['/var/work/django/main',
 '/usr/lib/python38.zip',
 '/usr/lib/python3.8',
 '/usr/lib/python3.8/lib-dynload',
 '/var/work/django/oscar/lib/python3.8/site-packages',
 '/var/work/django/django-oscar/src']

Server time: 	Fri, 02 Apr 2021 19:02:19 +0000
Traceback Switch to copy-and-paste view

    /var/work/django/oscar/lib/python3.8/site-packages/django/core/handlers/exception.py, line 47, in inner

                        response = get_response(request)

         …
    ▶ Local vars
    /var/work/django/oscar/lib/python3.8/site-packages/django/core/handlers/base.py, line 167, in _get_response

                callback, callback_args, callback_kwargs = self.resolve_request(request)

         …
    ▶ Local vars
    /var/work/django/oscar/lib/python3.8/site-packages/django/core/handlers/base.py, line 290, in resolve_request

                resolver_match = resolver.resolve(request.path_info)

         …
    ▶ Local vars
    /var/work/django/oscar/lib/python3.8/site-packages/django/urls/resolvers.py, line 547, in resolve

                            sub_match = pattern.resolve(new_path)

         …
    ▶ Local vars
    /var/work/django/oscar/lib/python3.8/site-packages/django/urls/resolvers.py, line 358, in resolve
```
