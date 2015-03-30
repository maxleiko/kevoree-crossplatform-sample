# Kevoree cross-platform sample

A simple KevScript that shows communications between a **Java** runtime, **Javascript** runtime and a **Browser** runtime

### Start the Java runtime
```sh
java \
 -Dnode.bootstrap=/path/to/crossplatform.kevs \
 -Dnode.name=javaNode \
 -jar kevoree.jar
```

### Start the Node.js runtime
```sh
kevoreejs -n jsNode --kevscript path/to/crossplatform.kevs
```

### Start the Browser runtime
Go to http://runjs.kevoree.org/#/kevscript:
 - Click **Upload a KevScript**
 - Select the **crossplatform.kevs** file
 - Enter **browserNode** as your start-up node name next to the **Start from KevScript** button
 - Click **Start from KevScript** button


All set :)