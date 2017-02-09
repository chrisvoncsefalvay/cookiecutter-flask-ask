{{ cookiecutter.skill_name }}
=============================

{{ cookiecutter.skill_short_description }}

Setup
-----

It is recommended to run this project in a virtualenv. If virtualenvs are unfamiliar to you, `this handy tutorial`_
might be a good place to start.

#.  Create a virtualenv for this project, and activate it.
#.  Use ``pip install -r requirements.txt`` to install the required Python packages.
#.  You will require ``ngrok`` to make your skill accessible to Alexa for testing. You can download ngrok `here`_.

.. _here: https://ngrok.com/download
.. _this handy tutorial: http://docs.python-guide.org/en/latest/dev/virtualenvs/

Quickstart
----------

Follow these easy steps to test your brand new Flask-Ask project.

#. Launch the server by invoking ``python {{cookiecutter.repo_name}}.py``.
#. With the server running, start ``ngrok http {{cookiecutter.port}}``.
#. Configure your app on the `Alexa Developer Portal`_. `This video`_ by `John Wheeler`_ shows how to deploy your speech assets configuration to the `Alexa Developer Portal`_.
#. That's all! If you are using a browser that supports WebRTC for micophone input (Chrome, Firefox or Opera), you may use `echosim`_ to test your script - simply log in with the same credentials you used to deploy your Skill.

.. _Alexa Developer Portal: https://developer.amazon.com/alexa
.. _This video: https://alexatutorial.com
.. _John Wheeler: https://alexatutorial.com/flask-ask/
.. _echosim: http://www.echosim.io/
