# Installing

The snippets should go in `~/Library/Application Support/Sublime Text 2/Packages/User`

If you are using git you can `clone https://github.com/jls/st2-snippets ~/Library/Application Support/Sublime Text 2/Packages/User` otherwise you will need to download the zip and extract to that directory.

# Snippets

### enyokind 

Creates a new enyo kind

### changed

Adds a new method for _attr_Changed.

	attrChanged: function(oldValue)
	{
		
	},
	
### over

Adds a method with a call to `this.inherited`.

	methodName: function()
	{
		this.inherited(arguments);
	},
	
### handle

Adds a method that has the arguments for an event handler.

	handleEventName: function(sender, event)
	{
	
	},

### fn

Adds a method defined on an object literal.

	fnName: function()
	{
	
	},
