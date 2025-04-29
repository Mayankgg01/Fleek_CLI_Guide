<div align="center">

# 👨🏻‍💻 **Fleek CLI Guide** 👨🏻‍💻

</div>



# **Pre-Requirements 🛠**

# **Install node.js & npm**

* node.js

```
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
```

```
sudo apt install -y nodejs
```

* npm

```
sudo apt install nodejs npm
```



# **Install fleek CLI**

```
sudo npm install -g @fleek-platform/cli
```

* Verify the Installation with

```
fleek
```

![image](https://github.com/user-attachments/assets/15e245da-e927-4b12-9f18-05e6e1ab9a45)



# **Login**

```
fleek login
```



* Run the above command to get the login page link:

* Login with your Wallet and Email (both)

* After login, open the above link again to sign 


![image](https://github.com/user-attachments/assets/afcc79a4-8a59-4636-82dd-7f1f1ff53e5b)

* Back to Terminal & u could see a success message:

![image](https://github.com/user-attachments/assets/3fe8e711-bef5-477f-8e34-fe4e00f4771e)



# **Create a project**


```
fleek projects create
```

* This will promt u to enter a project name: Enter anything u like:


* 🔺🔺 If u see somethink like that (check ss given below), than dont do anythink, just do next process of `Set up a simple page`

![Screenshot 2025-04-28 165908](https://github.com/user-attachments/assets/c6162abc-e6ce-473e-8793-8783f09acf78)




# **Set up a simple page**


  * Create a New Directory

```
mkdir ~/fleek-quick-start
```

  * Navigate to it

```
cd ~/fleek-quick-start
```

  * Create a simple html page inside `~/fleek-quick-start`

```
echo "Hello world" > index.html
```




# **Setup a Fleek site**

```
fleek sites init
```

  * This will promt u to do many thinks, just follow the CLI instructions

  * You’ll have to enter a name for the new site.

  * This will Promt `✔ Please specify the directory containing the site files to be uploaded` just enter `.`     (a dot)

  * This will promt `✔ Would you like to include the optional "build" command?` just enter `no`

  * This will promt `✔ Select a format for saving the site's configuration:`     just select  `JSON (fleek.config.json)` & Enter

  * Check the below given SCREENSHOT for more clarification

  ![image](https://github.com/user-attachments/assets/605b04dd-c428-45e9-8036-adb995e1d778)

  

# **Deploy the Fleek site**

```
fleek sites deploy
```

![image](https://github.com/user-attachments/assets/0c586dbd-70e6-4135-bb26-83351b991f6f)


Done!⚕️✅

👉 Join TG for more Updates: https://telegram.me/cryptogg

If U have any issue then open a issue on this repo or Dm me on TG~

Thank U! 👨🏻‍💻

 Happy Coding💗
















