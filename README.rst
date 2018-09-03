=============
Jumbotron4
============

Jumbotron4 is a simple Django bootstrap home page that use a bootstrap 
jumbotron4 style

Detailed documentation is in the "docs" directory.

Quick start
-----------

1. Add "jumbotron4" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'jumbotron4',
    ]

2. Include the bootstrap4web URLconf in your project urls.py like this::

    path('home/', include('jumbotron4.urls')),

3. Run `python manage.py migrate` to create the polls models.

4. Start the development server and visit http://127.0.0.1:8000/admin/
   to create a poll (you'll need the Admin app enabled).

5. Visit http://127.0.0.1:8000/polls/ to participate in the poll.
