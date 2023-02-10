<h1>Performing Symmetric Encryption</h1>


<h2>Description</h2>
In this lab, I learned to perform symmetric encryption. Symmetric encryption uses a single key to encrypt and decrypt data.
<br />



<h2>Environments Used </h2>

- <b>Kali GNU/Linux rolling</b> 

<h2>Utilities and Language </h2>

- <b>Terminal</b>

<h2>Program walk-through:</h2>

<p align="center">
From the desktop go to the left sidebar and click terminal then in the terminal type in an "echo Welcome to uCertify! > test.txt"  <br/>
<img src="https://i.postimg.cc/283Ztv4L/Screen-Shot-2023-02-09-at-4-26-06-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
  
  
<br />
Now type in "cat test.txt" to view the contents of the file   <br/>
<img src="https://i.postimg.cc/rwKvZ8yN/Screen-Shot-2023-02-09-at-4-50-45-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />



<br />
Continue by typing in "gpg -c test.txt" to encrypt the files using a symmetric key.  <br/>
"gpg" (GNU privacy guard) command encyrpts and signs your data and communication <br>
"-c" encyprts with symmetric cipher only <br>
this parameter as well as the command ask for a passphrase <br>
make the passphrase complex and strong<br>
<img src="https://i.postimg.cc/KY80MXps/Screen-Shot-2023-02-09-at-4-55-41-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />




<br>
now type in "cat test.txt.gpg" command to show encyrpted test.txt file <br>
you will notice encypted message appears <br>
now type in the command "gpg -o output.txt test.txt.gpg" to decrypt the message<br>
<img src="https://i.postimg.cc/kXLKq0Wd/Screen-Shot-2023-02-09-at-5-00-32-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />




<br />
Now type in "cat output.txt" to view the content of the output.txt file <br>
<img src="https://i.postimg.cc/JnY4jdVQ/Screen-Shot-2023-02-09-at-5-32-09-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />





















