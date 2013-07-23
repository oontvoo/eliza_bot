Eliza bot
=============
(mostly to be used with <a href="https://github.com/oontvoo/bash-irc-bot">bash-irc-bot</a>)

This is a simple implementation of an `eliza`. You can modify `src/main/resources/eliza/script` file to add different rules for it.


1) To build the package

   `mvn clean package`

This will generate an executable `jar` file under `./target/`

2) To run the executable 

   `java -jar eliza-bot.jar [<path to custom script>]`

   (Note: If you do not specify a new script, the default one, which is packaged into the `jar` will be used)
   
