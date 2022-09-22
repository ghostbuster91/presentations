Armadillo - typesafe jsonrpc api

Although jsonrpc is not the most popular protocol, nowadays mostly replaced by grpc, there are still places that use it, 
especially in the case of inter-process communication. The two most popular ones are blockchains and language server protocol. 
Up until now, there was no idiomatic scala library for building api using that protocol. 
I would like to present the work that we did at IOG that resulted in the creation of a new library - armadillo, 
that takes similar approach to the commonly known, and well received library for building http endpoints - tapir. 
As its older brother, armadillo allows you to describe your jsonrpc endpoints using pure values and later 
interpret them to your liking - be it http server or openrpc documentation. 
