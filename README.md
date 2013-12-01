It's recipe of [bluepill](https://github.com/bluepill-rb/bluepill) for Mac OS X.

Install:

```
bundle
./start.sh
```

Show status:

```
sudo bundle exec bluepill status
```

Manage programs:

```
sudo bundle exec bluepill stop postgres
sudo bundle exec bluepill stop redis

sudo bundle exec bluepill start redis

sudo bundle exec bluepill restart redis
```


It's manage program:

* Postgresql
* Redis

I recommend to use [homebrew](http://brew.sh/) for package manager.
