- Both event sourcing and a persistent store should be optional so that it can be used for sanitising and authenticating requests that will be sent into an event sink
- All integrations should be done with some kind of plugin interface to allow maximim customisability
- Do validators need the annotation passed? Would the simplicity of not having it be better?