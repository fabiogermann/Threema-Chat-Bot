# Threema-Chat-Bot

#### This is an Fork of [Sec42/3ma-bot](https://github.com/Sec42/3ma-bot)

It is written in go. If this is your first time working with go, you need to setup 
~~~Shell 
$GOPATH 
~~~ 
similar to this if you use Z-Shell, otherwise dot it in ~/.bashrc:
~~~Shell
"export GOPATH=~/.go" >> ~/.zshrc
export GOPATH=~/.go"
mkdir $GOPATH
go get github.com/o3ma/o3rest
go get github.com/o3ma/o3
~~~

Add ID to admins.txt like:
~~~Shell
HR2R2S1G #Testuser
~~~

Compile your Bot with:
~~~Shell
cd $HOME/threema-chat-bot
go build simple-bot.go privileges.go
~~~

Execute 
~~~Shell
./start_bot 
~~~
And Enjoy your Bot

### Universal Tool For Everything -- Threema Chat Bot

This bot is written mostly in perl.  Most of the features require some
external data to be downloaded and parsed into the correct format.
Check the `URLs` file in each subdirectory for pointers to data
sources.

### Usage
Build and run with go run simple-bot.go.

It will create an threema ID file on first run which will be saved to threema.id. I suggest add this to your backup and do not publish it.

The addressbook of the people that communicate with your bot will be saved to address.book if you kill the bot.

All incoming text messages will be passed on to a binary utfe.bot, and the output will be sent back to the originator.

This utfe.bot binary/script is not part of this repo and can be written in any language. Use your own imagination, or refer to [utfe](https://github.com/Sec42/utfe)

### Licence

All code in this repo is herby licenced under the 2-clause BSD licence. 

### Legacy


### Thanks

Thanks to:
[Sec42](https://github.com/Sec42)
[darth-veitcher](https://gist.github.com/darth-veitcher)
