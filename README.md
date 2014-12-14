# potato setup

### Workspace
It's a little difficult to explain how to setup. However - once it's up and running it's simple to work with. You'll need:

*Eclipse
*Spring Tool Suite (you can get as an eclipse plugin, or you can download the entire version of eclipse dedicated to it)
*Apache Tomcat 7 (http://tomcat.apache.org/download-70.cgi)
*Ivy (eclipse plugin)
*Github (eclipse plugin)

### Clone Repo in Eclipse
After those are all installed, you'll prolly need to restart eclipse. Fork the repository: https://github.com/ddmills/potato. Once you have those things installed and working, go to

1. Eclipse ->
2. file ->
3. import ->
4. project from git ->
5. Clone uri ->
6. enter info + follow steps

The root folder is called "CyShop" - i dunno why, but don't try to change it or it'll probably break.

### To get the server working:

1. window ->
2. show view ->
3. "servers" (a panel should come up labelled "servers") ->
4. right click in pane ->
5. new->
6. server ->
7. tomcat v7 ->
8. server runtime environment (add) ->
9. browse to installed directory of tomcat 7 ->
10. finish ->
11. finish

Now there should be a "tomcat v7.0 Server at localhost" in your servers pane.

1. Right click the server ->
2. add and remove ->
3. push "CyShop" to the right side ->
4. finish

### Resolving Errors

With Ivy installed there is a button in your toolbar labelled "Resolve All" to the left of the green "run" button. It has green and yellow arrows going in circles. That button should hopefully fix problems, try to click every time it before running. You can also right click on the server in the pane, and do "clean tomcat work directory", you can also right click the "CyShop" listed under the server and do "Clean Module Work Directory" - these will sometimes fix errors.

### Localhost

Once the server is running and the app is attached, the project will be on your localhost at: http://localhost:8080/FlashPotato/controller/main/view/

Um good luck. It can be a frustrating process.
