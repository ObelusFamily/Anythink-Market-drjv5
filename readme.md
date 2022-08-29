# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone the repo
	git clone https://github.com/ObelusFamily/Anythink-Market-drjv5.git
2. From the project's root directory, load Anythink's backend and frontend using Docker
	docker-compose up
3. Test that the backend is running
	http://localhost:3000/api/ping
4. Test the frontend is connected by creating a new user
	http://localhost:3001/register
