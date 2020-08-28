# ios-pod-template
This is a iOS template repo with the basic setup to build an iOS pod. It builds the entire pod structure, including tests and an Example app. It's already integreated with Travis :)

## Setup the initial repo

### Branch setup
- Our main branch is blocked, no one has permision to push directly, you must do a pull request

### Initialize the Pod
For initializing the pod first we need to setup the right version of CocoaPods. In order to avoid versions conflicts, we use bundler to unify our version.
```
$ bundle install
```

Now we are ready to setup the pod structure:
```
$ bundle exec pod lib create [POD_NAME] --template-url=git@github.com:Covitba/pod-template
```

