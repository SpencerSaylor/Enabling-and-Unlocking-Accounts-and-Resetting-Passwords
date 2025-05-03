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

<p>
  5. Attempt to log in with it 6 times with a bad password
</p>

<p>
  6. Observe that the account has been locked out within Active Directory
</p>
  
<p>
  7. Unlock the account
</p>

<p>
  8. Reset the password
</p>

<p>
  9. Attempt to login with it
</p>

<h2>Enabling and Disabling Accounts</h2>

<p>
  1. Disable the same account in Active Directory
</p>

<p>
  2. Attempt to login with it, observe the error message
</p>

<p>
  3. Re-enable the account and attempt to login with it.
</p>

<h2>Observing Logs</h2>

<p>
  1. Observe the logs in the Domain Controller
</p>

<p>
  2. Observe the logs on the client Machine
</p>
