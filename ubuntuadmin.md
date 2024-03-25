Using UBUNTU Lamp server we installed in previous project we can now perform some of the basic administrative tasks, like adding FTP to the server, creating users and a web page.
So, to start let's add FTP to this server from the command line:

![Picture14](https://github.com/mikekad1/firewallsandvpns/assets/62948569/f4f17a06-b7d0-4669-a189-2424b36e761f)

After successful installation, we can create two users: user1 and user2:

![Picture15](https://github.com/mikekad1/firewallsandvpns/assets/62948569/36ab9390-647b-45cc-9545-a9cd927a816a)

(I added passwords to both users for this project)

We can than use FTP to upload file to each user's home directory to verify that everything is working correctly:

![Picture16](https://github.com/mikekad1/firewallsandvpns/assets/62948569/fc6438a1-919f-4f32-a6c4-e05cf99a3024)

(verified it is password protected, there is no alternative home directory encryption available due to LVM)

Let's make sure that user2 can read files in user1's home directory:

![Picture17](https://github.com/mikekad1/firewallsandvpns/assets/62948569/8f121a6e-df18-4baa-a0f5-84413865dc2a)

Great! Now let's put this to use, upload a picture and see if we can display it as a webpage:

![Picture18](https://github.com/mikekad1/firewallsandvpns/assets/62948569/1f12aea9-956f-4335-988f-13dde5fb387a)

(I used my college information here, you will need to use your own imagination for an index page)

Finally, let's install phpMyAdmin:

![Picture19](https://github.com/mikekad1/firewallsandvpns/assets/62948569/4ba4b7ff-17e8-482f-a927-a0fb9f479432)

We can varify if the log on works:

![Picture20](https://github.com/mikekad1/firewallsandvpns/assets/62948569/6c1ade2d-d321-4166-ad52-c7b72eb5918c)

Let's also verify that php-mbstring is installed:

![Picture21](https://github.com/mikekad1/firewallsandvpns/assets/62948569/6b55fa00-dfca-496d-ae0b-0f6103ca2a43)

We should also check if gettext is installed:

![Picture22](https://github.com/mikekad1/firewallsandvpns/assets/62948569/27908a9e-abd7-48b4-b9d0-0cdbeac88b72)

(we could optionally also install mcrypt, but it is unsupported by this version of Ubuntu)

Next, let's restart the service and install iptables:

![Picture23](https://github.com/mikekad1/firewallsandvpns/assets/62948569/f34fa055-39e5-4844-81b0-0c78efa0548a)

All done!
