# Kata 02

## Virtual Enviroment - *python*
Create a virtual enviroment using the Terminal.

* Using the command ``python3 -m venv env``.

* By creating ``venv``, automatically creates files like: env and source.

![ls venv](/LaunchX/Kata02/01.png "env&source")

* Execute the line command ``source env/bin/activate`` to activate the ``venv``. You can see ``(env)`` at the beginning of your command line. 

![venv activate](/LaunchX/Kata02/02.png "venv activate")

## Install a library

* First use ``pip freeze`` to check wich libraries you have installed now in your enviroment. (you shouldn`t have any installed).

* Now use ``pip install `` to install a library.
    * Install ``python-dateutil`` library.

![install packages](/LaunchX/Kata02/03.png "pip install")

* If you want to check how many libraries you have now, use ``pip freeze`` again and it will show you wich libraries are installed.

![freeze](/LaunchX/Kata02/04.png "pip freeze")

## Deactivate venv

* You can deactivate your ``venv`` by using ``deactivate``.

![deactivate](/LaunchX/Kata02/05.png "deactivate venv")

* To know if the enviroment was deactivated, ``(env)`` doesn`t have to show up.

### That`s it :smile: you created a virtual enviroment :file_folder:. Congrats!! :thumbsup: :tada: :sunglasses:

