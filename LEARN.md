- Component(), Inject(), Input()

- Reserve the constructor for minimal initialization such as wiring constructor parameters to properties. The constructor shouldn't do anything. It certainly shouldn't call a function that makes HTTP requests to a remote server as a real data service would.