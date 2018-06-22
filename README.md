# RemoteUsabilityTests
Simple Small Tool for performing remote Usability Tests and recording results.
Requires MongoDB.
Depends on: Seaside / VoyageMongo

## Installation
```smalltalk
 (IceRepositoryCreator new
  	url: 'git@github.com:juliangrigera/RemoteUsabilityTests.git';
  	createRepository) updatePackage: #TasksLogger.
 (Smalltalk at:#TasksLoggerScriptsRunner) prepareForDevelopment
```
