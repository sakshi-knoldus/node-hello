# Node Hello World

Simple node.js app that servers "hello world"

Great for testing simple deployments to the cloud

## Create a .tgz file

`npm pack`

## Run It

`npm start`

### Ports Used:
`http://localhost:3000
http://localhost:3001`

### Url of first Server Repository is:
`http://3.15.46.174:3000/
http://3.15.46.174:3001/`

### Url of second server Repository is:
`http://3.143.249.197:3000/
http://3.143.249.197:3001/`

### Command used to connect to your EC2-Instance

ssh -i EC2-Instance.pem ubuntu@ipAddress

### Command used to run the Jenkins

Install the war file `jenkins wget https://get.jenkins.io/war-stable/2.263.2/jenkins.war`
Run the jenkins `java -jar jenkins.war`


