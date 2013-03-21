# WebService::HabitRPG - Perl interface to the HabitRPG API

## To install (stable version)

    cpanm WebService::HabitRPG

You'll probably find it useful to have a `~/.habitrpgrc` file that
looks like the following:

    [auth]
    user_id   = xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx
    api_token = xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx

You can get these values by going to Settings -> API in HabitRPG.

Use `hrpg` without any arguments to see command line help.

You can find documention of the stable release on the CPAN:

* https://metacpan.org/module/WebService::HabitRPG
* https://metacpan.org/module/hrpg

## To develop / contribute

* Fork this repository
* Install Dist::Zilla (`cpanm Dist::Zilla`)
* `dzil build`

You can install the built module with `cpanm WebService-HabitRPG-*.tar.gz`
