To automatically log in to your server using the Putty utility, you need the utility itself

`https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html`

also need to specify the IP address and server name in the `putty`. Next, we create any `*.bat` file in which we specify the path to the utility for executing the script, the server name, login and password.

`cd %ProgramFiles%\Putty\
start putty.exe -load HOSTNAME -l USERNAME -pw PASSWORD`

you can also download a copy of the script
[example.zip](https://github.com/koliasa/koliasa/files/10127656/example.zip)
