<h1>Simple CTF</h1>


> Export the IP
<code>export IP=10.10.157.157</code>

> How many services are running under port 1000?
2

> What is running on the higher port?
ssh

> What's the CVE you're using against the application? 
 <code>CVE-2019-9053</code>
 ```
 <code> python2 exploit.py -u url -w rockyou.txt [-p]</code>
 salt=1dac0d92e9fa6bb2
 [-p] didn't actually find the password so try using hydra with the same wordlist
 username = mitch
 ```
> To what kind of vulnerability is the application vulnerable?
 <code>sqli</code>

> What's the password?
 <code>secret</code>

> Where can you login with the details obtained?
 <code>ssh</code>
 ```
 [2222][ssh] host: 10.10.157.157   login: mitch   password: secret
 ```

> User flag
G00d j0b, keep up!

> Is there any other user in the home directory? What's its name?
 <code>sunbath</code>

> What can you leverage to spawn a privileged shell?
  <code>vim</code>can be run as root without password

> Root Flag 
 <code>W3ll d0n3. You made it!</code>