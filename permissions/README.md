0. My name is Betty
Create a script that switches the current user to the user betty.
#!/bin/bash
su betty

1. Who am I
Write a script that prints the effective username of the current user.
#!/bin/bash
id -u

2. Groups
Write a script that prints all the groups the current user is part of.
#!/bin/bash
groups

3. New owner
Write a script that changes the owner of the file hello to the user betty.
#!/bin/bash
sudo chown betty hello

4. Empty!
Write a script that creates an empty file called hello.
#!/bin/bash
touch hello

5. Execute
Write a script that adds execute permission to the owner of the file hello.
#!/bin/bash
chmod u+x hello

6. Multiple permissions
Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
#!/bin/bash
chmod ug+x+o+r

