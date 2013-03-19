# WebService::HabitRPG - Perl interface to the HabitRPG API

Currently under development. If you're super-eager:

* Fork this repository
* Install Dist::Zilla (`cpanm Dist::Zilla`)
* `dzil build`

You can install the built module with `cpanm WebService-HabitRPG-*.tar.gz`

You'll probably find it useful to have a `~/.habitrpgrc` file that
looks like the following:

    [auth]
    user_id   = xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx
    api_token = xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx

You can get these values by going to Settings -> API in HabitRPG.

The command line client can be used with:

* `hrpg status` -- show basic character information
* `hrpg dump` -- dumps all character information (for debugging)
