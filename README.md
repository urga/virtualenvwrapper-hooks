INSTALLATION

1. Go to your virtualenvwrapper directory where you keep your virtualenvs, $HOME/.virtualenvs by default.
2. git clone... .


HOOKS

Currently there are 2 hooks that have extra stuff in them: postactivate and predeactivate.
It's setup so that if you swith to a virtualenv, the environment is expanded with variables that are defined in your project directory's .env file.
After deactivating, the previous environment is restored.
