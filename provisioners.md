# Provisioners in Terraform
#### -In Terraform, provisioners are used to run scripts or commands on your machines after they have been created.
#### -This is useful if you need to set up something on your new server, like installing software, or doing some setup steps.

# Types of Provisioners
#### 1.remote-exec Provisioner: Runs commands on a remote machine (like a server you just created).
````
https://developer.hashicorp.com/terraform/language/resources/provisioners/remote-exec
````
#### 2.local-exec Provisioner: Runs commands on your local machine (the computer you're running Terraform from).
````
https://developer.hashicorp.com/terraform/language/resources/provisioners/local-exec
````
#### 3.file provisioner: Used to copy files from your local machine to a remote machine.
````
https://developer.hashicorp.com/terraform/language/resources/provisioners/file
````
