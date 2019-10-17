This is a guide to run chisel3 bootcamp by using Ammonite.

Ammonite environment to run Chisel3 bootcamp.
Ammonite Repl 1.7.4   
Scala 2.12.10
Java 1.8

Download amm:  sudo sh -c '(echo "#!/usr/bin/env sh" && curl -L https://github.com/lihaoyi/Ammonite/releases/download/1.7.4/2.12-1.7.4) > /usr/local/bin/amm && chmod +x /usr/local/bin/amm' && amm

@ val path = System.getProperty("user.dir") + "/load-ivy.sc"
@ interp.load.module(ammonite.ops.Path(java.nio.file.FileSystems.getDefault().getPath(path)))
@ // others code

