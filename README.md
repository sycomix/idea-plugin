AI.codes IntelliJ plugin
-------------------------

This plugin works together with AI.codes dashboard, to provide
better code completion for IntelliJ.

Building IntelliJ plugin is notoriously tedious. This process will be improved in future.

* Clone the IntelliJ community version source code from github. This will be served as the plugin **SDK** (basically it is what plugin in compiled against).
* Download either IntelliJ community or ultimate editor, as your editor. This is where you edit the code.
* Clone this repo, in IntelliJ, use "Import Project" to open this project. IntelliJ should automatically import it as a plugin project. If not, you may have to create a new Plugin Project, and then clone the code into that empty folder.
* To build a plugin, use "Build -> Prepare Plugin". This will generate a zip/jar file that can be installed.
