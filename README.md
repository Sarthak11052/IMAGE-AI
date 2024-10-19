```markdown
# IMAGE-AI

A web application that leverages the OpenAI API to generate images based on personalized prompts. Users can share their generated images in a community gallery, along with creator details and the associated prompt. The app allows for easy downloading of images and promotes a creative, collaborative environment.

## Features
- **Image Generation**: Users can create images using custom text prompts with the help of the OpenAI API.
- **Community Gallery**: Share your creations with others. View images alongside details such as the creator’s name and prompt.
- **Image Download**: Easily download your generated images to your local device.
- **User-Friendly Interface**: Built with a modern and intuitive design for easy navigation and interaction.

## Tech Stack
- **Frontend**: React, Vite
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Image Hosting**: Cloudinary
- **AI API**: OpenAI API

## Project Setup

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/IMAGE-AI.git
   cd IMAGE-AI
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory and add the following:
   ```env
   OPENAI_API_KEY=your-openai-api-key
   CLOUDINARY_CLOUD_NAME=your-cloudinary-cloud-name
   CLOUDINARY_API_KEY=your-cloudinary-api-key
   CLOUDINARY_API_SECRET=your-cloudinary-api-secret
   MONGODB_URI=your-mongodb-uri
   ```

4. Run the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:3000`.

## Usage
- Enter a prompt to generate an image.
- After generation, you can upload the image to the community gallery with your details.
- Browse the gallery to see other users' creations.
- Download any image directly from the gallery.
