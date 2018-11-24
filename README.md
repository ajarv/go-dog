"# go-dog" 


oc new-app --template=go-s2i -p APPLICATION_NAME=hello -p GIT_URI=https://github.com/ajarv/go-dog.git -p APPLICATION_HOSTNAME=hellogo.cloudapps1.origin.com -p GO_MAIN=server