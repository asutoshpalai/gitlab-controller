# gitlab-controller
This has been created to automate the task of handling ssh keys for gitlab by admin
##### Note:This repo is no longer maintained. It has been shifted to [sdslabs/gitlab-controller](https://github.com/sdslabs/gitlab-controller)

##Requirement
requests

pip install requests

##Available commands are:
    addkey <username> <key>
    removekey <username>
    changekey <username> <key>
    adduser <email> <username> <password> <Full Name>
    removeuser <username>

    ####Note:put the sshkey in quotes as shown below

##Examples
./run.py addkey asutoshpalai "ssh-rsa fkadsjfkljadskfjlkdjlkadsjfkljdasklfjkldsjfkdfjfljadsklfjladsjfkljadslkfj mail@example.com"  
./run.py removekey asutoshpalai
