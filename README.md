Murder
====

The easiest way to kill that stupid service that you can't figure out how to end.

```sh
$ meteor
# Can't listen on port 3000. Perhaps another Meteor is running?

$ murder meteor
# 7764    killed   /home/vagrant/.meteor/packages/meteor-tool/.1.0.33.k69mx++os.linux.x86_64+web.browser+web.cordova/meteor-tool-os.linux.x86_64/dev_bundle/bin/node
# 7824    killed   /home/vagrant/.meteor/packages/meteor-tool/.1.0.33.k69mx++os.linux.x86_64+web.browser+web.cordova/meteor-tool-os.linux.x86_64/dev_bundle/mongodb/bin/mongod

$ meteor
# Meteor server running on: http://localhost:3000/
```
