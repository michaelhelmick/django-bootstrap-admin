Django Bootstrap Admin
======================

`Django-Bootstrap-Admin` is a collection of files in attempt to pretty up the Django admin with @Twitter's [Bootstrap](http://twitter.github.com/bootstrap/ "Bootstrap") components.

Please
------
Feel free to fork and change styles in the `less` directory or update the `Makefile`, I didn't give much attention to that :P


Usage
-----

1. Copy the `project/admin/static` and `project/admin/templatetags` directory into **your** `project/admin` directory.
2. Copy the `project/admin/templates` directory into **your** `project/admin` directory.
3. Update `settings.py` to make sure that your static directories/paths, etc. are linked up correctly. (Also, update your database, and run `./manage.py syncdb` or use the sample one I provided [root user: admin, root pass: admin])
4. Go to project root and run `./manage.py collectstatic`
5. `runserver` and go to http://localhost:8000/admin (or wherever you're pointing your application to run on)

TODO
----
* Pretty up the Calendar javascript popout links
* Pretty up the Time selection javascript popout