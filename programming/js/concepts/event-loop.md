Event Loop
===========

Event Loop is related to the internal event processing mechanism in JavaScript. It simply is like the following code

	while (message = getNextMessage()) {
		processMessage(message)
	}

Here message is any event that is either system generated (like UI event for click) or a user generated event.