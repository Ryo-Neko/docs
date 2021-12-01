# SSH on Windows using PowerShell

## Turn on the OpenSSH option

1. Press Windows button and type 'add' directory. Then open "Add or remove programs".
![add](pics/add.png)

2. Press "Optional features"
![of](pics/press_of.png)

3. Press "Add a features"
![press_af](pics/addaf.png)

4. Search "SSH". Then install ***"OpenSSH Client"*** (NOT Open SSH Server like the below figure)
![client](pics/searchsshcli.png)

5. Reopen PowerShell and make sure the ssh command is avairable.
```shell
ssh
```
If there is no error, ssh client is successfly installed. Congrats🎉