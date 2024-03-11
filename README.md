https://twitter.com/silennai/status/1666838148725219329

## Running the Project Locally

This document will guide you through the process of setting up and running this Next.js project on your local machine.

### Prerequisites

You need to have [Node.js](https://nodejs.org/en/) and [npm](https://www.npmjs.com/) installed on your local machine.

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/SilenNaihin/roadmanai.git
   ```

2. Navigate into the project directory:

   ```bash
   cd roadmanai
   ```

3. Install the project dependencies:

   ```bash
   npm install
   ```

### Configuration

This project uses environment variables for configuration. These are stored in a `.env.local` file at the root of the project.

1. Copy the provided `.env.template` file:

   ```bash
   cp .env.template .env.local
   ```

2. Open the newly created `.env.local` file and fill in your API keys for Eleven and Openai.

### Running in Development

To open a development server, use Vercel to correctly build Python runtime routes.

1. Install Vercel CLI:

   ```bash
   npm i -g vercel
   ```

2. Run the development server:

   ```bash
   vercel dev
   ```

Your app should now be running on [http://localhost:3000](http://localhost:3000).

You are now ready to start developing! Changes you make in your files will automatically update the app in the browser.

### Further Help

If you have any issues setting up the project or running the server, feel free to create an issue or reach me at [https://twitter.com/silennai](https://twitter.com/silennai). I'll be happy to help :)

#### The Future?

Talking avatar from uploaded pics?

- https://elai.io/getting-started-with-api
- https://www.deepbrain.io/
- https://www.heygen.com/avatars
- https://www.d-id.com/api/

Accent in any style

- Prompt: Person
- Description (if person isn't famous): Description of person
- Voice: upload mp3 or link yt vid

Tech

- Switch to Node backend for streaming Whisper, 3.5, Eleven
