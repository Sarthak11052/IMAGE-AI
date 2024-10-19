

# IMAGE-AI
A web application enabling users to generate images using personalized prompts through the OpenAI API. Users can share their creations in a community gallery, showcasing the image alongside creators’ details and prompts, with an option to download the generated images.

## Features

- **Image Generation**: Leverage the power of OpenAI API to generate unique images based on user-provided prompts.
- **Community Gallery**: Users can share their generated images, which are displayed alongside the creator's details and the corresponding prompts.
- **Download Option**: Users can easily download the generated images.
- **Streamlined Hosting**: The application is built for fast performance and seamless user experience using modern web technologies.

## Demo

Check out the live web app [here](https://cosmic-arithmetic-abc61a.netlify.app/).

## Tech Stack

- **Frontend**: React, Vite
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Cloud Storage**: Cloudinary
- **API Integration**: OpenAI API

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/IMAGE-AI.git
   cd IMAGE-AI
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory and add the following:
   ```bash
   OPENAI_API_KEY=your_openai_api_key
   MONGO_URI=your_mongo_db_connection_string
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   ```

4. Run the app:
   ```bash
   npm run dev
   ```

   The app should be running on `http://localhost:3000`.

## Usage

- **Generate Image**: Users can enter a prompt and click "Generate" to create an image.
- **Share Creation**: After generating an image, users can choose to share it in the community gallery with their details and the prompt used.
- **Browse Gallery**: Explore the community gallery to see other users' creations.
- **Download**: Users can download the images directly from the gallery or after generating them.
