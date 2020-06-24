## Summary

The developers have indicated that they'll need a mongodb database soon. We need to create a provisioning script that will create this server.

Research the method for installing and configuring a MongoDB server on your server.

Write the steps in to the provisioning script.

Start the machine and run the tests as follows:

1. Vagrant up from within the starter code directory
2. vagrant provision to setup run all the provision code linked
3. vagrant reload to reload the virtual machine
4. cd tests
5. rake spec
6. all tests should return working with no failures

## Hints

To get MongoDB to listen on 0.0.0.0 is a very minor change to the mongodb.conf file.

Research how this is done. But consider how you can automate the editing of this file with your provisioning script. 

> HINT: You cannot edit a file with a provisioning script so you'll have to come up with another solution.





