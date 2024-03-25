For this project we are going to install a Ubuntu LAMP server from command line, connect to the network and update and upgrade the OS.
First we are going to install LAMP:

![Picture1](https://github.com/mikekad1/firewallsandvpns/assets/62948569/64a9a30f-4b57-42a9-8ac1-1b3278d57746)

![Picture2](https://github.com/mikekad1/firewallsandvpns/assets/62948569/bae6465e-088e-4954-b8f9-e39e767eb156)

Our next step is installing SSH:

![Picture3](https://github.com/mikekad1/firewallsandvpns/assets/62948569/c00d5b6e-fb07-4291-979b-954a163d869c)

After installation finishes we can then set password ‘passwordmysql’ to mysql:

![Picture4](https://github.com/mikekad1/firewallsandvpns/assets/62948569/ee3d83d4-7373-4882-8e93-9e0d6367a57d)

We can hange admin username to first initial and last name…

![Picture5](https://github.com/mikekad1/firewallsandvpns/assets/62948569/cdf18a0f-2791-4361-8da6-78ba9dfa5fc7)

and password to ‘password1’:

![Picture6](https://github.com/mikekad1/firewallsandvpns/assets/62948569/0913bbca-d4da-4967-99a3-3d54721ac9d3)

(also I created admin for MySQL with the same credentials)
After this, I changed hostname to a random number:

![Picture7](https://github.com/mikekad1/firewallsandvpns/assets/62948569/21e5614c-e18a-4337-87ca-f81955272b60)

I also updated entry in ‘hosts’ and ran an update:

![Picture8](https://github.com/mikekad1/firewallsandvpns/assets/62948569/ec0187e5-0513-4bee-883f-939a48b4a11c)

...almost forgot to upgrade...:(

![Picture9](https://github.com/mikekad1/firewallsandvpns/assets/62948569/4bacd518-896a-40fe-a3fa-448522719c1f)

I than eplaced ‘index.html’ with a provided code

![Picture10](https://github.com/mikekad1/firewallsandvpns/assets/62948569/35809d21-44be-489b-82fc-86db6eaac272)

Which resulted in this page, we can see out hostsname on it:

![Picture11](https://github.com/mikekad1/firewallsandvpns/assets/62948569/8f0775ae-b0c2-4a72-8372-e8c4ca79a2f8)

We can check our databases now:

![Picture12](https://github.com/mikekad1/firewallsandvpns/assets/62948569/2fc7ccc2-71b3-42eb-89c2-68d3446b2f3d)

..and we can also now view the tables:

![Picture13](https://github.com/mikekad1/firewallsandvpns/assets/62948569/edb64f2a-e071-42ff-9edf-1e934abcc117)

Looks like everything is working as it should :)
