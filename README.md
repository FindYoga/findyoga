<p align="center">
  <img alt="FindYoga" src="http://i.imgur.com/QLK2rH9.png">
</p>

<p align="center">
	Site by <a href="http://www.thinkmill.com.au">Thinkmill</a>. Made with <a href="http://keystonejs.com">Keystone.js</a>.
</p>


# Publishing to Production

## Clone the dev repo from github

	git clone https://github.com/Thinkmill/findyoga-au-site

## Add live remote

Server must know your public ssh key; ask @molomby

	git remote add live ssh://git@brahman.findyoga.com.au/srv/git/findyoga-au-site.git

## Push to production repository

	git push live


# Installation

	$ git clone git@github.com:Thinkmill/findyoga-au-site.git findyoga
	$ cd findyoga
	$ npm install
	$ npm link
	$ node keystone

**NOTE:** In development a hostname of `findyoga.dev` is assumed, so add that to your `/etc/hosts`.


# Accounts

## Google Maps API

*Currently using the free-tier Google Maps API, limit is 25,000 request per day*

- Account:			`jed@findyoga.com`
- API key:			`AIzaSyDG80tO7x0lfo9kPpC8U9kIhE-gWwOAo-s`
- Referers:
	- `*.findyoga.com/*`
	- `*.findyoga.com.au/*`
	- `localhost/*`
	- `fy/*`
	- `fy.dev/*`
	- `findyoga/*`
	- `findyoga.dev/*`
	- `findyoga.herokuapp.com/*`
- Server API key:	`AIzaSyBr9fadvRtK2ifXM4soKg1lIm4TiR_LAvo`
- *No server IPs defined*

## Facebook

### Development

 - App ID:		`10152497365400205`
 - App secret:	`ef3b23642e924f08fce2bea7ce279027`
 - Site URL:	`http://findyoga.dev:3000/`

### Production

 - App ID:		`60801910204`
 - App secret:	`ecac073fe71500c82d843129c028be99`
 - Site URL: 	`http://www.findyoga.com.au/`

## Embedly

- API Key:		`70e1d302c7b54f4c8f26144c6b7f427e`
- Username:		`jed@findyoga.com`
- Password:		`LB9RHeKxUSVQM7UMX68RwMeQujl8qJcR`

## Cloudinary

- Username:		`jed@findyoga.com`
- Password:		`wEP68w6Uj56sm9M5WDZ58fm1mjAJX0lx4VF5Me4JweuVB5wUXu1pp7i4PxjwzLFx`
- Cloud name:	`fy`
- API Key:		`295176372525568`
- API Secret:	`_rjuIm4PLxgX6DRIU_6uq0uZwsU`

## Mandrill

- Username:		`jed@findyoga.com`
- Password:		`b24opChZR12443338e5GMp664811387Z74d733SpX3820o3wjDr67gEk11jF3891`
- API Key:		`00tEjsjexOVrI561lqAMKQ`

## MongoLab

### Admin account

- Username:		`findyoga`
- Email:		`jed@findyoga.com`
- Password:		`Wc6XvFwumgv8JJkQCMLKSPudwV6CYAUZgXUBzm5T9qcQeUBJy9rs6f3gsQyr5c76`

Note: to import, change to the folder with the .bson files in it. Then use `pwd` to get the path, and paste it at the end of the command.
# findyoga
