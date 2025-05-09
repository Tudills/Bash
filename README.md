# Bash
Experimentation using Bash Programming/Shell Scripting

---

## What do first? ##
05/08/2025
### Goal: Execute a script remotely using this very repository. ###

I intend on writing a simple bash code, and using one of my virtual machines to grab the script using the "git" command
this is going to be something incredibly simple. A print within the terminal box saying, "Hello World." There is no need for 
an exclamation point, it isnt that impressive.

![Hello world](https://github.com/user-attachments/assets/d4929c72-cc93-4919-90cd-1fbe73af8a42)

Success.

---
 
## Now What? ##
05/08/2025
### Goal: Execute a script remotely that runs a standard update within linux. ###

Initially all I had intended to do was update an instance of kali using a script from my github, which is really silly honestly. BUT something really neat happened. 
I haven't used my Kali instance for a few days, and when I would try and update my release, I would get an error. I found out that this was not just an error for me, But for every Kali user.
NEAT!

![Kali Keyrings](https://github.com/user-attachments/assets/c2cea449-a85a-4d1d-a035-5d0d8349c6f9)

after I used the prompt 
       
       sudo wget https://archive.kali.org/archive-keyring.gpg -O /usr/share/keyrings/kali-archive-keyring.gpg
    
I continued on with my project. Anyway.
I manually deleted my "Bash" Directory within my Downloads via

      sudo rm Bash -r

I then went back and grabbed the same folder I did before and copied it back into my downloads, and then 

     bash update

![Update](https://github.com/user-attachments/assets/c1c9d101-476e-41cc-aac6-7e9b07f62dc9)

Success.

