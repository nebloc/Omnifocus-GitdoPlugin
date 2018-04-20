# Omnifocus Gitdo Plugin

This is a plugin for [Gitdo](https://github.com/nebloc/Gitdo), a tool for tracking TODO comments in code.
It requires Omnifocus Pro as the basic version does not allow scripting. Omnifocus is a **Mac Only** application and this plugin needs `osascript -l JavaScript` for the interpreter.

# Install:
```
git clone https://github.com/nebloc/Omnifocus-GitdoPlugin.git ~/.gitdo/plugins/Omnifocus
```

The plugin is designed to add a task to a certain project, with a context of "waiting" that is paused, therefore hiding the task based on your perspective settings.

It asks for a project name to add the tasks to, and also a remote link to use in the description. More information on the remote links can be found [here](https://github.com/nebloc/Trello-GitdoPlugin#remote-link).

If you need to change the configuration at any point, it can be found in 
```
.git/gitdo/plugins/Omnifocus/

# Or

.hg/gitdo/plugins/Omnifocus/
```
