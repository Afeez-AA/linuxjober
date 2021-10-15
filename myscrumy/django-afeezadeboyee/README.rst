=====
afeezadeboyee
=====

afeezadeboyee is a simple Django app to conduct web-based polls. For each 
question, visitors can choose between a fixed number of answers.

Detailed documentation is in the "docs" directory.

Quick start
------------

1. Add "afeezadeboyee" to your INSTALLED_APPS settings like this::

    INSTALLED_APPS = [
        ...
        'afeezadeboyee',
    ]

2. Include the afeezadeboyee URLconF in your project urls.py like this::

    path('afeezadeboyee/', include('afeezadeboyee.urls')),

3. Run 'python manage.py migrate' to create the afeezadeboyee models.

4. Start the development server and visit http://127.0.0.1:8000/admin/
   to create a afeezadeboyee (you'll need the admin app enabled).

5. Visit http://127.0.0.1:8000/afeezadeboyee/ to participate in the afeezadeboyee.