# retropilot-client
React client for Retropilot


Ties into https://github.com/retropilot/retropilot-server/ to provide a react frontend

## Environment Variables

The app configuration (see `src/config.js`) is loaded from environment variables. A different
different environment can be configured for development (`npm run start`), testing (`npm test`) and
production (`npm run build`).

To override the environment variables, create a `.env.local` file. You can also override the
variables for development, testing and production independently (`.env.development`, `.env.test.local` and `.env.production.local`
files). Set the `API_URL` to the address of the RetroPilot server, such as `http://localhost:8080` or `https://api.retropilot.local`.
