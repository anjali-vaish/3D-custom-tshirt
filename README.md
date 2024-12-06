### README.md

# AI-Powered 3D Product Website 

This project is a step-by-step tutorial on building an AI-powered, 3D product-based website using **React**, **Three.js**, and other modern web development tools. This beginner-friendly course demonstrates how to integrate 3D rendering and customization features, allowing users to interact with and personalize products like T-shirts in real-time. 

## Features
- Dynamic 3D product customization (e.g., color, texture, and logos).
- AI integration for generating unique textures or logos using custom prompts.
- Real-time rendering and reflection updates.
- Responsiveness across all devices.
- Clean and scalable code architecture.

## Technologies Used
- **Three.js**: For 3D graphics rendering.
- **React 3 Fiber**: React renderer for Three.js.
- **Tailwind CSS**: For styling.
- **Framer Motion**: For animations.
- **React Color**: For color selection.
- **DALL-E AI**: For generating unique images and textures.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/anjali-vaish/3D-custom-tshirt
   cd threejs
   ```
2. Navigate to the `client` directory:
   ```bash
   cd client
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up Tailwind CSS:
   - Add Tailwind CSS directives to `index.css`.
   - Configure `tailwind.config.js` paths.

5. Start the development server:
   ```bash
   npm run dev
   ```
6. Open the application in your browser at `http://localhost:3000`.

## Folder Structure
```
client/
├── public/            # Static assets and 3D models
├── src/
│   ├── assets/        # Images and icons
│   ├── config/        # Constants, helpers, and motion utilities
│   ├── pages/         # Home and customizer pages
│   ├── canvas/        # Components for 3D rendering
│   ├── App.jsx        # Main application
│   └── index.jsx      # Entry point
```

## How It Works
1. **Home Page**: Displays information about the website and introduces the customization feature.
2. **T-Shirt Customizer**: Enables users to:
   - Change the T-shirt color.
   - Upload custom logos or textures.
   - Use AI to generate unique designs.
3. **3D Rendering**: Utilizes `Three.js` and `React 3 Fiber` for real-time rendering.

## Deployment
The project is hosted using **Hostinger** with a custom domain. To deploy:
1. Set up hosting and domain via Hostinger.
2. Use the provided file manager to upload and host your build.

## Resources
- [Three.js Documentation](https://threejs.org/docs/)
- [React 3 Fiber Documentation](https://docs.pmnd.rs/react-three-fiber/getting-started/introduction)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Framer Motion Documentation](https://www.framer.com/motion/)

---

**Credits**: Inspired by Anderson Manchini’s 3D project with additional features. For an in-depth course on 3D modeling, visit Anderson's [course link](#).

---

## Contributing
Feel free to open issues or submit pull requests to improve this project.

## License
This project is licensed under the MIT License. 


