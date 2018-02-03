# HW1

CSC-DevOps Spring 2018: HW1

Name: Rishi Jain

Unity ID: rjain9

## Steps in setup

1. Created 3 Vitual Machines using vagrant- server for running ansible scripts, server for Coffee Maker and server for Slenium tests.
2. Created an ansible playbook hw1-playbook.yml which performs 2 roles- (a) coffeeserver (b) seleniumserver.
3. Created a main.yml in both the roles which has tasks for coffee maker server and selenium test server respectively.
4. Got the VMs up and running and executed the following command in the ansible server-
```
ansible-playbook hw1-playbook.yml -i inventory -vvv
```

## Screencast

Click [here](https://youtu.be/a5N1LYOzeLA) to view the screencast for HW1.
