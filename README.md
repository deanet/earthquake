gempabumi di terminal lebak bulus ;p
=====

Diambil source code dari [https://github.com/jugyo/earthquake](https://github.com/jugyo/earthquake)  

###Syarat dan ketentuan: 
	`ruby versi 1.9`
	`lib ssl dev` *apt-get install libssl-dev*

###Cara Install:

####download source
`git clone git://github.com/deanet/earthquake.git`

####Install dependecis:
`# cd earthquake`
`# cat dep.xt | xargs gem install`

####cara jalanin
`./earthquake/bin/earthquake`

####akan terlihat:

####1) open: https://bla bla bla..

buka link diatas, klik authorized app, kopi nomornya

####2) Enter the PIN: 

masukan nomor/pin token

tadaa...

![http://images.cjb.net/fdae2.png](http://images.cjb.net/fdae2.png)

cara gunain silahkan baca manual `ketik :help`

log installasi bisa dilihat di ![https://gist.github.com/1020329](https://gist.github.com/1020329)

Usage
----

### Launch

    $ earthquake

Commands
----

### Tweet

    ⚡ Hello World!

### Show

    ⚡ $xx

**$xx** is the alias of tweet id.

### Reply

    ⚡ $xx hi!

### Delete

    ⚡ :delete $xx

### Retweet

    ⚡ :retweet $xx

### Timeline

    ⚡ :recent
    ⚡ :recent jugyo

### Lists

    ⚡ :recent yugui/ruby-committers

### Search

    ⚡ :search #ruby

### Eval

    ⚡ :eval Time.now

### Exit

    ⚡ :exit

### Reconnect

    ⚡ :reconnect

### Restart

    ⚡ :restart

### Threads

    ⚡ :thread $xx

### Install Plugins

    ⚡ :plugin_install https://gist.github.com/899506

### Alias

    ⚡ :alias rt retweet

And there are more commands!

see [https://github.com/jugyo/earthquake/wiki](https://github.com/jugyo/earthquake/wiki)

Copyright
----

Copyright (c) 2011 jugyo. See LICENSE.txt for further details.
