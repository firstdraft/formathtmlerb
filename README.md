formathtmlerb
===================

This plugins adds a new html erb formatter to C9 based on htmlbeautifier.

Requirements
------------

 * gem install htmlbeautifier


Installation on c9.io
---------------------

Run the following in c9 terminal:

    # Create a folder
    mkdir ~/.c9/plugins

    # Clone the plugin
    git clone https://github.com/firstdraft/formathtmlerb.git ~/.c9/plugins/formathtmlerb

    # Click Cloud9 -> Open Your Init Script and add the below code
    services.pluginManager.loadPackage([
      "~/.c9/plugins/formathtmlerb/package.json",
    ]);

    # Refresh the page

License
-------

formathtmlerb is licensed under the AGPL version 3
