# https---github.com-andreysyniy-locallibrary

# Attention!!!

<!-- SECRET_KEY. This is a secret key that is used as part of Django's website security strategy. If you're not protecting this code in development, you'll need to use a different code (perhaps read from an environment variable or file) when putting it into production. -->

<!-- DEBUG. This enables debugging logs to be displayed on error, rather than HTTP status code responses. This should be set to False in production as debug information is useful for attackers, but for now we can keep it set to True. -->

# ------------------------------------------------------------------------------------------------------------------

# Migration

# commands:     python manage.py makemigrations
#               python manage.py migrate

<!-- Warning: You'll need to run these commands every time your models change in a way that will affect the structure of the data that needs to be stored (including both addition and removal of whole models and individual fields).

The makemigrations command creates (but does not apply) the migrations for all applications installed in your project. You can specify the application name as well to just run a migration for a single project. This gives you a chance to check out the code for these migrations before they are applied. If you're a Django expert, you may choose to tweak them slightly!

The migrate command is what applies the migrations to your database. Django tracks which ones have been added to the current database. -->

# ------------------------------------------------------------------------------------------------------------------