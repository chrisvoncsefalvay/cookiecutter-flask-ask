Flask-Ask cookiecutter
======================

This cookiecutter creates a ready-to-roll Alexa Skill skeleton based on `Flask-Ask`_, an amazing framework by `John
Wheeler`_. Flask-Ask is quite possibly the fastest way to get started with developing Alexa Skills, and this
cookiecutter only makes it faster!

What's in the box
-----------------

- A Flask Python application, including handlers for session start, launch and a number of built-in ``AMAZON`` intents, such as ``Yes``, ``No``, and ``Help``.
- A sample welcome intention that shows the way templating works in Flask-Ask, as well as a ``template.yaml`` template file with some examples.
- A ``speech_assets`` folder, to hold your speech assets.
- An (empty, but gitkeep'd) ``custom_slot_types`` folder to keep your list of custom slot values.
- An ``intent_schema.json``, which you can use as your template for building up the intent schema.
- An empty ``sample_utterances.txt`` file (since the intentions currently provided for don't need utterances...).
- A ``requirements.txt`` file with all you need.
- A ``README.rst``, explaining requirements and the setup process.

Short of a partridge in a pear tree, this contains everything you might need to get cracking with your very own Alexa skill! Read on below for directions on getting started with `Flask-Ask`_.


Setup
-----

To create the scaffolded project skeleton in your project, all you need to do is

1. make sure you have ``cookiecutter`` installed (if not, go `here`_),
2. get ``cookiecutter`` to pull this repo and start scaffolding by entering the following command into your shell of choice: ``cookiecutter gh:chrisvoncsefalvay/cookiecutter-flask-ask`` , and
3. follow the instructions in the ``README.rst`` file in your brand new repo!

That's all!


Contribute
----------

Contributions are welcome! I'm also on the `Flask-Ask Gitter`_ a lot, so you are welcome to let me know just what I
could do to make this an even better tool for Alexa developers!


.. _here: https://github.com/audreyr/cookiecutter
.. _John Wheeler: https://alexatutorial.com
.. _Flask-Ask: https://alexatutorial.com/flask-ask
.. _Flask-Ask Gitter: https://gitter.im/johnwheeler/flask-ask/
