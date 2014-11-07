tsuru_plugin_app-git-remote
===========================

Simple [tsuru
plugin](http://docs.tsuru.io/en/latest/using/cli/plugins.html) to
display just the app's tsuru git remote and nothing else

Example usage:

    $ tsuru app-git-remote -a my-cool-app
    git@tsuru.mycompany.com:my-cool-app.git

    $ cd my-cool-app
    $ tsuru app-git-remote
    git@tsuru.mycompany.com:my-cool-app.git
