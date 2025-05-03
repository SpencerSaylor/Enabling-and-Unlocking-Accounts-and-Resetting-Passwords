<p align="center">
<img src="https://i.imgur.com/ji8tw98.png" width="50%" height="50%"/>
</p>

<h1>Enabling and Unlocking Accounts and Resetting Passwords</h1>
</b>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Dealing with Account Lockouts</h2>

<p>
  1. Get logged into dc-1
</p>

<p>
  2. Pick a random user account you created previously
</p>
  
<p>
  3. Attempt to log in with it 10 times with a bad password
</p>

<p>
  4. Configure Group Policy to Lockout the account after 5 attempts: [How to Configure Account Lockout Threshold in Group Policy](https://docs.google.com/document/d/1msUMWaPDMR1hPYxzGOlgN4KpUjnyyYEv3vvOQXkSpLQ/edit)
</p>
