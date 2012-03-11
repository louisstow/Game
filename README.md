#Game
This is a mini library intended to be a quick and unobtrusive library for building HTML5 games. It provides
the utter basics

    Game.tick(function(dt, frameNumber) {});
	Game.render(function(ctx) {});
	Game.input(function(type, eventObject) {});
	
From these basic functions you can create your own flavour of a game engine.

This is built from the article here: http://louisstow.tumblr.com/post/19103446204/unobtrusive-game-engines