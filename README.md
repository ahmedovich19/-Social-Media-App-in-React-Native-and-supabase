# Full Stack Social Media App

<!-- Add the course description image here if available -->
<!-- ![Course Description Image](./image.webp) -->
<p align="center"><img align="center" width="700" src="./image.webp"/></p>

This is a full-stack social media application built using **React Native** and **Supabase**. The project was developed following the "Build Full Stack Social Media App in React Native with Supabase" course, which covers essential features for a modern social media platform. The app is designed to be responsive, feature-rich, and compatible across multiple platforms.

## Features

- **Responsiveness**: The app adapts seamlessly to different screen sizes and orientations, ensuring a great user experience on both Android and iOS devices.
- **Rich Text Editor**: Users can create posts with formatted text, including bold, italics, lists, and hyperlinks, using an integrated rich text editor.
- **Realtime Updates**: The app leverages Supabase's real-time capabilities to provide instant updates for posts, likes, comments, and notifications.
- **Media Uploading**: Users can upload images and videos to enhance their posts.
- **Media Sharing**: Share uploaded media content with other users directly within the app.
- **Image Caching**: Implements image caching to improve performance by reducing load times for frequently accessed media.
- **SVG Icons**: Utilizes scalable vector graphics (SVG) icons for a lightweight and customizable user interface.
- **Cross-Platform Compatibility**: Built with React Native, the app runs smoothly on both web, Android, and iOS platforms.

## Technologies Used

- **React Native**: A framework for building native mobile apps using JavaScript and React.
- **Supabase**: An open-source backend-as-a-service providing authentication, a PostgreSQL database, real-time subscriptions, and file storage.
- **Expo**: Used for managing the React Native development environment and cross-platform deployment.

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- Expo CLI
- A Supabase account and project (for backend services)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add your Supabase project credentials:
     ```
     SUPABASE_URL=your-supabase-url
     SUPABASE_ANON_KEY=your-supabase-anon-key
     ```

4. Start the development server:
   ```bash
   npx expo run:android -d
   ```
   ```bash
   npx expo run:ios -d
   ```

### Running the App

- Use the Expo Go app on your mobile device or an emulator to scan the QR code displayed in the terminal.
- Alternatively, press `a` to run on Android or `i` for iOS in the terminal.

## Usage

- **Sign Up/Login**: Register or log in using email and password (or social login if configured).
- **Create Posts**: Use the rich text editor to compose posts and upload media.
- **Interact**: Like, comment, and share posts in real-time.
- **Profile**: View and manage your profile with uploaded media and activity.

