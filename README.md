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


### Manage my runtimes
You can now retrieve your running model in the [Kevoree Web Editor](http://editor.kevoree.org/?host=ws.kevoree.org&port=80&path=crossPlatform)

> If you want to push modifications to your nodes you must use **Model** > **Custom push**  
> and specify:
>  - host: **ws.kevoree.org**
>  - port: **80**
>  - path: **crossPlatform**