# AWS Notes

### Connecting to the Machine
1. Go to AWS EC2 dashboard (aka the AWS console).
2. Select the EC2 instance, click **Actions**, Instance State, Start. <br>
When the machine starts, it gets assigned an IP address.
Once the instance status turns green, the instance is running and you can connect to the machine.
3. Open a terminal on your computer and `cd .ssh`, which is where ssh keys are stored. 
4. ```ssh -i id_rsa -L localhost:8888:localhost:8888 ubuntu@##.##.###.###``` <br>
Replace the # with the IP address from the AWS console under **IPv4 Public IP.** <br>
When you run this command, you have to have the id_rsa file, which is the private key so it can match up with the public key that was given to the AWS machine. It also maps port 8888 of your computer to port 8888 of the remote machine. <br>

#### Making a second connection
Once you've connected the first time from a terminal, you can open a second terminal and make a new connection. The second time, you don't need to map the ports. You can just say <br>
```ssh -i ~/.ssh/id_rsa ubuntu@<your IP address>```

### Running Jupyter Notebook from the AWS Machine
+ Once you're in the terminal for the AWS machine, type `jupyter notebook` 
+ Copy the link that it says to copy
+ Paste it into browser
+ Now you can run Jupyter Notebooks on the remote machine :)
