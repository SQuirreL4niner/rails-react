# README

*<h3>URL</h3>

<h2>https://ror-react-1234.herokuapp.com/</h2>

Things you may want to cover:

* Ruby version
	
	3.3.1

* System dependencies

	Moment, jQuery, SCSS, React

* Configuration

	Standard RoR w/React plugin

* <strong>This app uses React with ES5</strong>


* Database creation

	Standard embedded sqlite3 for dev

	PostGreSQL for production

* Database initialization

	rake db:migrate to initalize <i>after</i> model has been generated

	rake db:schema:load to clear the db



* How to run the test suite

	N/A

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

	Local Dev: 'rails s'

	Fire up sublime 'subl .'

	For Heroku you need the cli use this command
		wget -qO- https://cli-assets.heroku.com/install-ubuntu.sh | sh

		heroku push master to deploy
		heroku log (locally) to check out logs
		heroku run rake db:migrate to register PostgreSQL in web

* NOTES

	You need some plugins for Sublime to enjoy this

	<b>You need Sublimes 'Package Control' plugin</b>
		There are links online to install w/python script


	To install and fire up these plugins, just ctrl+shift+p
	and search for plugin. Follow any instructions for 
	plugin readme's to enable


	Babel plugin
	Haml plugin
	Ruby
	(could use a little Emmit plugin also for autocomplete)
