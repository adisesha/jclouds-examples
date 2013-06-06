# blobstore-scala-filesystem
This is a simple example command line client that creates a container, and 'test' file in a [BlobStore](http://jclouds.incubator.apache.org/documentation/userguide/blobstore-guide/)
using 'filesystem' api in scala. This example uses [scala-arm](https://github.com/jsuereth/scala-arm) for managing [BlobStoreContext](http://javadocs.jclouds.cloudbees.net/org/jclouds/blobstore/BlobStoreContext.html)
## Build
Ensure that sbt is installed. Tested with 0.12.2
## Run
Go to root of project and run sbt. Invoke 'run basedir'. 'basedir' is the folder where the container, and file will be stored

Ex. If your basedir is '/home/blobstore'

run '/home/blobstore'
## License
Licensed under the Apache License, Version 2.0