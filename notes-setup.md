# Setup

These are some notes for preparing your computer for Code Camp.

1. _(This first step is optional but highly recommended for securing your computer.)_ Harden your computer so rogue software can't take
advantage of your everyday user having administrator privileges

   a. Create a new user on your machine with username `admin` and password also `admin` (or something else meaningful to you). 

   b. Log out your regular user, log in as `admin` and take away administrator rights from your regular user. 

   c. Then log out as `admin` and back in as your regular user. 
  
   d. From now on, when you install software or make system changes, you'll be prompted to provide the `admin`/`admin` credentials to 
   authorize whatever you are doing.
  
   e. When you install software from the command line that requires administrator privileges, you'll do something like the following:

```bash
$ su admin   #<- grants you temporary admin privileges
$ password: <enter your admin password>
$ # ... software install, whatever...
$ exit   #<- pops you back to regular user
```

2. Install [iTerm2](https://iterm2.com) so you have a good terminal for doing work at the command line.

3. Do you have a password manager? I recommend [1Password](https://1password.com) if you don't have one. Here is one feature of 1Password
that makes it worth it for me to pay for it: 1Password has an ssh-agent that can authenticate private keys that you've stored within 1Password.
This makes it super easy to user your private keys _with a passcode_ and interact with ssh, AWS servers, github, etc.

4. Install [homebrew](https://brew.sh). This is a package manager for the Mac that makes it easy to install many different types of software that you run from
the command line. 

5. The default shell on Mac OS was changed from bash to zsh. I prefer bash. Here are some [instructions](https://itnext.io/upgrading-bash-on-macos-7138bd1066ba) for installing it with homebrew.

6. Install java 8 and java 11 (and maybe even java 17) and also jenv to be able to easily switch versions.

7. Install Clojure and Clojure CLI.

8. Install git. Create a github account, also install Github Desktop.

9. Install VS Code.

10. Install Calva (a VS Code extension for Clojure).

